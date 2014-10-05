Quick-ADT-Proj
==============

quick envirment setting


Remember 

1.you should use android-ndk-r8e

2.APP_CPPFLAGS must add -std=gnu++0x

3.<quick-cocos2d> Derictory can not in your root dir
  
  example:
      APP_CPPFLAGS := -frtti -Wno-error=format-security -fsigned-char -std=gnu++0x -Os $(CPPFLAGS)
