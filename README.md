# XNotepadCore
Core of notepad for using in c# projects

## What features are there?

### (File Menu)
- Create new window
- Create new file
- Save file
- Open File
- Close window
- Exit

### (Edit Menu)
- Clear
- Undo
- Redo
- Copy
- Paste
- Date
- Set text box zoom
- Change font

## How to use?
You have the right to make changes to the core.

1.Create WinForms project.

2.Add **XNotepadCore** to the project root.

3.Add a button or another clickable object.

4.Write a script from a template.

```c#
private void yourButton_Click(object sender, EventArgs e)
{
    XNotepadCore.OpenFile(richTextBox1, openFileDialog1, this);
}
```
5.Rather than **<XNotepadCore.OpenFile>** you can write any of functions of block **"What features are there?"**.

## Requirements for each function

### (File Menu)
- Create new window -> **(Form)**
- Create new file -> **(RichTextBox, Form)**
- Save file -> **(RichTextBox, SaveFileDialog, Form)**
- Open File -> **(RichTextBox, OpenFileDialog, Form)**
- Close window -> **(Form)**
- Exit

### (Edit Menu)
- Clear -> **(RichTextBox)**
- Undo -> **(RichTextBox)**
- Redo -> **(RichTextBox)**
- Copy -> **(RichTextBox)**
- Paste -> **(RichTextBox)**
- Date -> **(RichTextBox)**
- Set text box zoom+ -> **(RichTextBox, ZoomMaxValue)**
- Change font -> **(RichTextBox, FontName, FontSize)**
