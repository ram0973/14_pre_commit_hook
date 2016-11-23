# Task [№14](https://devman.org/challenges/14/) from [devman.org](https://devman.org)
## Requirements
```
Python 3.5.2+
```
## Setup
```    
git clone https://github.com/ram0973/14_pre_commit_hook.git
cp pre-commit .git/hooks
chmod +x .git/hooks/post-commit
```
## Description
If the tests reveals an error, the commit will be canceled
## Usage
```
cd 14_pre_commit_hook
git commit -m "Some commit message"
```
## License
[MIT](http://opensource.org/licenses/MIT)