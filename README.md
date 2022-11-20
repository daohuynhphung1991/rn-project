# rn-project

#Run CocoaPods on Apple Silicon (M1)

# STEP 1: Install ffi
sudo arch -x86_64 gem install ffi

# STEP 2: Re-install dependencies
arch -x86_64 pod install
