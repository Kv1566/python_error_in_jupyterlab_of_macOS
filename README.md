# 【已解決】
# 【解決方法一】在程式一開始時加入兩行指令：
import os
os.environ['KMP_DUPLICATE_LIB_OK']='True'
# 【解決方法二】直接先 install nokml, 一勞永逸
conda install nokml
# python_error_in_jupyterlab_of_macOS
# 想麻煩有在macOS裡使用anaconda的朋友幫忙測試底下python程式碼能不能正常執行？！
# 會用到tensorflow及keras，還有matplotlib！
# 有借別人的windows機器跑anaconda跑過此程式碼完全沒問題，但我的macOS下跑的話會在最後一行imshow那裡crash掉，一直找不到原因為何！
# 我的機器：
macbook pro 2015mid + 16G RAM
macOS: 10.14.6
Anaconda Navigator: 1.9.12
Environments: 新建
Python: 3.6 及 3.7 及 3.8都試過
tensorflow: 2.0.0
keras: 2.3.1
matplotlib: 3.2.2 
JupyterLab: 2.1.5
Jupiter Notebook: 6.0.3
# 以上，在所借純Windows 10筆電測試成功者，其Python是3.6, tensorflow是2.1.0，其餘皆一樣！而且其RAM只有8G！
# 煩請高手指教！
