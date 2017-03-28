# mono-repo-test-subtrees

Test of making a mono repo from three existing repos using git subtrees. Commands run were:
```
git remote add android-subtree git@github.com:lnanek/mono-repo-test-android.git
git remote add ios-subtree git@github.com:lnanek/mono-repo-test-ios.git
git remote add react-native-subtree git@github.com:lnanek/mono-repo-test-react-native.git

git subtree add --prefix=android/ android-subtree master
git subtree add --prefix=ios/ ios-subtree master
git subtree add --prefix=react-native/ react-native-subtree master
```
