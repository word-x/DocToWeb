#DocToWeb, for tutorials, documentations and instructions
## Introduction
DocToWeb is an Office Word Add-in, which can convert a Word document to a responsive (PC/Mobile/Tablet) website with just one click. You can use it to write program documentation or some structural documents such as tutorials or product instructions.

Once I have tested many CMS, such as Wordpress, Joomla, Drupal, etc. Yes, they are all excellent systems developed by smart team, but I still think they are too heavy and complicated.

Because for most people, what they have on their computer is just Office Word and they have few knowledge about server or server side language like PHP. At that moment, an idea came to me that why we can’t just write our contents in Office Word and convert the Word document to a website with VBA.

With this in my mind, I developed DocToWeb and it did save me a lot of time and energy.

![Demo](https://github.com/ed0522/DocToWeb/blob/master/pcdemo.gif)

Demo site:http://www.word-x.com/en/demdoc_to_web_demo/websites/SimpleDocument/toc.html
## Features
- It can run on any computer with Office Word installed, no matter Windows or Mac.
- It can convert a 100 page word document to a responsive website in 3-5 seconds.
- You can put the website folder to anywhere, such as local disk, server, Github Page, etc.
- The website is responsive and looks good on different devices such as PC, mobile and tablet.
- It has several wonderful themes for you to choose.
## How to use?
1. Download all the files in this repository.
2. Rename DocToWebTemplate.docm as you want. You will write your structural content in this word document.
3. Open the word document after you rename it.
4. Fill in all document properties in the first page according to the template.
If some property is empty, the program will stop running and prompt unknown error. Please make sure all document properties are filled.
3. Start writing in the Word template.
4. Click "Run" on the first page to generate your clean and simple website with table of contents attached. Your website files will be shown in
C:\Users\Ed0522\Documents\GitHub\DocToWeb\doc_to_web_project\websites (for example)

## Supported Word features
- DocToWeb only support document with Heading1 and Heading2 title. The reason we don’t support Heading 3 title is because Heading 3 title makes the document too complicated and needs more time to revise. We just want keep everything stupid and simple (KISS). As an alternative, you can use Heading 2(1), Heading 2(2) instead of using Heading 3 title.
- For convenience, DocToWeb only supports one-column document.
- You can use Bold, Italic, Underline, Strikethrough, Subscript and Superscript for font. But we don't support any Font Color or Character Shading.
- You can use different font size, but finally it will be converted as the specified font size by our program.
- You can insert table, picture, shapes, chart and SmartArt as usual.
- You can insert any formula in Word.
- You can remove the list number for Heading 1 and Heading 2 of our Word template and it has no influence on our program.
- We don't support multilevel list, because multilevel list sometimes causes some strange problem in Word. Therefore, we should avoid this trouble. Please make sure don't use multilevel list.
## Note
- Please do not deelete the Document Properties table on the first page.
- Please do not change the theme or styles of word document because it may cause some unknown errors which make you unhappy. After all, there is no perfect program. It has Advantages and also Disadvatages.
- I recommend you don't change anything about the template.
- Do not use Japanese or Chinese character as folder name or parameter.
- If you don't want to insert ad code in your website, you can just delete adcodes folder.
## 国内的朋友，我就不给你们写中文版的说明了。
写这个VBA插件是为了写一些教程之类的结构性文档，大家可以用来作为CMS用也可以。
其实很简单，把所有文件下载下来，然后打开Word文档（DocToWebTemplate.docm）把第一页的表格填一下，然后开始写文档，写完文档后最后点击Run就可以了。
最后生成的网站文件夹在DocToWeb\doc_to_web_project\websites下面。
注意：不要用中文命名文件夹！
# Contact
- E-mail：ed0522@163.com
- Wechat： eddy5600
- Blog：http://zuli.life/
- Twitter: https://twitter.com/EddyWang0522, Sometimes I can't access to twitter for some reasons.

If you have any problems or just want to make friends with me, please feel free to write me an email or contact via wechat. 
I am looking forward to hearing from you.
