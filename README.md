**How to compile Windows using CMAKE-GUI**
1. Open **Git Bash** or **Github Destop**
 > `git clone https://github.com/AlexeyAB/darknet`
2. Compile on Windows using **CMake-GUI**
---
 ![How to compile on Windows using CMAKE-GUI](https://66.media.tumblr.com/865869bc79fb2a81ea69a189a7923094/af3a7a1d70f93c22-df/s540x810/3bd8dd820eb1221fe83edce3fce1dadda9f2ed61.png)
---
 >  * Paste the *PATH* of the clone file;
 >  * Add **/build** at the tail of the *PATH* at <**Where to build the binaries**>
 >  * Click **Configure** and choose the **Optional platform for generator** to **x64**;
 >  * Click **Generate**;
 >  * Click **Open Project**;
 ---
![Release Darknet](https://66.media.tumblr.com/7d7da4eae8af2012b39c573ab18ef7bf/af3a7a1d70f93c22-21/s540x810/58b0e47d79bba8c113b07b6669fd0c9b35f26066.png)
 ---
 >> * Set **Release**, **x64**
 >> * Click **Build** and choose **Build Solution**. Or press **Ctrl+Shift+B**
3. Build Success 
 --- 
  ![Build Success](https://66.media.tumblr.com/820244e83ea77e4870ba0d8400f663e7/af3a7a1d70f93c22-d8/s540x810/05e4f238e2ef1c11edce8eff7e6e964f84a883d9.png)
 ---
  ![Release Darknet](https://66.media.tumblr.com/7d7da4eae8af2012b39c573ab18ef7bf/af3a7a1d70f93c22-21/s540x810/58b0e47d79bba8c113b07b6669fd0c9b35f26066.png)
 --- 
 >>> * Set **Release**, **x64**
 >>> * Click **Build** and choose **Build Solution**. Or press **Ctrl+Shift+B**
 > 3. Build Success 
---
![Build Success](https://66.media.tumblr.com/820244e83ea77e4870ba0d8400f663e7/af3a7a1d70f93c22-d8/s540x810/05e4f238e2ef1c11edce8eff7e6e964f84a883d9.png)
---
**Installating Python2,3 on Windows**
> 1. Download **[ATOM](https://atom.io/)** and **[Python2&3](https://www.python.org)**
> 2. Open **Power Shell(run as administrator)** and **ATOM**;
> 3. Type ``pip --help`` on **PowerShell** 
> 4. Type ``pip install --upgrade pip``

**Installating [TensorFlow2](https://www.tensorflow.org/install/#download-a-package) on Windows using Python**
>  Open **Power Shell(run as administrator)** and type 
>>* `` pip install --upgrade pip``
>>* ``pip3 install --user --upgrade tensorflow  # install in $HOME``
>>* ``python3 -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"``
---
**NOTE**
> Potential ERROR: 
>>Could not install packages due to an EnvironmentError: [Errno 2] No such file or directory: 'C:\\Users\\pc\\AppData\\Local\\Packages\\PythonSoftwareFoundation.Python.3.7_qbz5n2kfra8p0\\LocalCache\\local-packages\\Python37\\site-packages\\tensorflow_estimator\\python\\estimator\\canned\\linear_optimizer\\python\\utils\\__pycache__\\sharded_mutable_dense_hashtable.cpython-37.pyc' 
>Solution:
>> Uninstall python then ReInstalled it again but this time after a successful reinstallation; at the last step, click **HAVE TO DISABLE THE PATH LENGTH LIMIT**
---
![HAVE TO DISABLE THE PATH LENGTH LIMIT](https://i.stack.imgur.com/wC9Pq.png)
