# Life After School GUI Application

**Console** version of the app: [Life After School Console](https://github.com/antoniacatrinel/Life-After-School-App-CPP/tree/main/Life%20After%20School%20Console)

### Requirements
- Implement the interface design (location and size of GUI widgets, without attached functionalities) using **Qt 6.3.0 framework**, without using the Qt Designer.
- The list or table displaying the repository entities in administrator mode should be populated using an input file.
- Add a filter for your repository and filter the elements according to any criteria you choose using the textChanged event of the QLineEdit. The elements are filtered by the substring in the line edit box above the list.
- Add a gradient to one of the widgets on your interface (e.g. the list, a button, etc).
- Add multiple *undo* and *redo* functionality for the `add`, `remove`, and `update` operations. Implement this functionality using inheritance and polymorphism. You will have **Undo** and **Redo** buttons on the GUI, as well as a key combination to undo and redo the operations (e.g. `Ctrl+Z`, `Ctrl+Y`).
- Show the contents of the `user event list` using a table view. You must use the [Qt View/Model](https://doc.qt.io/qt-5/modelview.html) components (`QTableView`). Create your own model – a class which inherits from [`QAbstractTableModel`](https://doc.qt.io/qt-5/qabstracttablemodel.html). This window will be opened from your GUI main window.
