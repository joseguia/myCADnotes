# myCADnotes
collections of random CAD notes - tips tricks from the inter-webs-tubes
lots of information floating around in regards to what I'm working on, so I wanted a place to house everything accesbile from any device I may happen to be on.

kinda like a blog  - saw a few other devs use this to stash links to resources, so I figured what the heck

if I forget to give credit for something you wrote, drop me a line or comment, I want to be sure everyone gets proper credit, but also - you might have a newer better version of what Im sharing here, win win =)

-------------------------------------------------------
[AutoCAD StartUp Order](https://github.com/joseguia/myCADnotes/wiki/AutoCAD-Loading-Order-(good-info))
" .. On startup, the first things AutoCAD loads are its CUI files. It first loads the Enterprise CUI file, then the Main CUI file, then any partial CUI files attached to the Main, then any partial CUI files attached to the Enterprise. I have no idea of the reasoning behind this slightly strange order, but  .."
-------------------------------------------------------
[_Config.lsp](https://github.com/joseguia/myCADnotes/blob/main/_Config.lsp)
This file (forgot where I absconded it from - if its yours let me know) shares a lot fo the system variables in cad that we may overlook or forget about until something acts wonky. good for a reset kinda routien, although I also include resetting my text and dimstyles as well for a full reset.
-------------------------------------------------------
[_CustomShortcuts.lsp](https://github.com/joseguia/myCADnotes/blob/main/_CustomShortcuts.lsp)
This bad boy is from a fellow git user [dtgoitia](https://github.com/dtgoitia/civil-autolisp/commits?author=dtgoitia)
examples :
  (defun c:iso() (command "_.isolateobjects") ..
  (defun c:iso() (command "_.isolateobjects")..
  (defun c:uiso() (command "_.unisolateobjects")..
  (defun c:c ( / ent_name ); Fast copy ..
  (defun c:m ( / ent_name ); Fast move ..
  (defun c:p0() ;;paste blk at 0,0 ..
  (defun c:n() (command "_.NCOPY" ..
  (defun c:t () (command "_.textedit" ..
  (defun c:pp()(command "_.publish" ..
  (defun c:BYR ;Set bylayer recursive ..
  (defun c:c0() ;;copybase blk at 0,0 ..
  (defun c:cl ( Close selected polylines ..
-------------------------------------------------------
