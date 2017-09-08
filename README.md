# boost-compile

Boost.Build setup

    Open Command Prompt and navigate to C:\Program Files\boost_1_59_0\tools\build.
    run bootstrap.bat  编译生成msvc版本的bjam.exe b2.exe
    Run bootstrap.bat mingw.
    
    Run b2 install --prefix="C:\Program Files\boost-build".
    Add C:\Program Files\boost-build\bin to Windows PATH.
    利用VC版本的b2生产gcc版本的boost库
    b2  --prefix="C:\Program Files\boost" toolset=gcc install

boost building

    Open Command Prompt and navigate to C:\Program Files\boost_1_59_0.
    Run

b2  --prefix="C:\Program Files\boost" toolset=gcc install
