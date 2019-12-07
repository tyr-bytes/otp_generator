# otp_generator

### INSTALL ###
python3 -m venv env
pip3 install -r requirements.txt
chmod +x submission.py
./submission

###  USAGE  ###
usage: submission.py [-h] (--generate-qr | --get-otp)
	--generate-qr generates a .PNG file named "mccabmic_qr" 
	in the current directory

	--get-otp generates a one-time OTP code
	that can be used to authenticate
