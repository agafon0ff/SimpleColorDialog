# Simple ColorDialog Qt
![ColorDialog](https://user-images.githubusercontent.com/13070282/80280230-7e34c900-870b-11ea-911e-eea664ae9337.png)

Example:
```c++
ColorDialog colorDialog;
if(colorDialog.exec() == QDialog::Accepted)
    qDebug() << colorDialog.getColor(); //"#070"
```
