# RefreshLayout 刷新控件

# Add it in your root build.gradle at the end of repositories:
    allprojects{
        positories {
            ..
            maven{
                url 'https://jitpack.io'
                }
            }
         }
# Step 2. Add the dependency
    dependencies{
       implementation 'com.github.mraben:RefreshLayout:V1.0'
    }
