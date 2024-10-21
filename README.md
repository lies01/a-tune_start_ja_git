# a-tune_start_ja_git
The python scripts and helps of a-tune. With this, you can start playing movie (with press space key by this script) on just the time you input.

Firstly download this folder by click the green **<>code** bottun, and **Download ZIP**. Then, Unzip in your download folder. If you unzip in other folder, change **~/Download** to the path of the unzipped folder in the codes in this text.

## for WindowsOS
Just execute "~/Download/a-tune_start_ja_git/a-tune_start_ja7_WindowsOS/a-tune_start_ja7/dist/atune_startja7.exe"

You may receive warning like below image from your PC. Then, click **More info**, and click **Run**.
![waning image](https://github.com/user-attachments/assets/88ce5935-333f-45b0-b74c-bc12ef6f4c6e)

## for MacOS
Open "tarminal" application on your PC. Then, input below code.
`cd ~/Download/a-tune_start_ja_git/a-tune_start_ja7_MacOS`

To install requirements for the file, input this code on the terminal.
`pip3 install -r requirements.txt`
(if you have some error, pls install or upgrade **pip3** with below codes on terminal)
install
`sudo apt install python3-pip`
upgrade
`pip3 install pip --upgrade`

When you succeeded, input below code and make app file on your PC.
`pyinstaller atune_startja7.py --onefile`

Finally, you can execute the app file, "~/Download/a-tune_start_ja_git/a-tune_start_ja7_MacOS/dist/atune_startja7"
