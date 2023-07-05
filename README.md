# Galaxy-book2-750XEW-ubuntu-installing- KnowHow


##  1. 이미지 구울 때 NTFS로 굽기
##  2. 부팅 시에는 Safe Graphic로 해서 내장 그래픽이 아닌 LLvmpipe로 부팅(나중에 설정해줄거임)
##  3. 설치 끝난 후에 grub 에서 'e'를 누른뒤에 quiet splash의 뒤에 nomodeset를 추가하고 ctrl+x를 눌러서 부팅
##  4. After Nomodeset Booting(Using llvmpipe graphics) type in Command Window
##  systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target 
## 5.  And then reboot
## 6. Finally You can resolve auto sleep mode when you booting ubuntu after 1 Minute
