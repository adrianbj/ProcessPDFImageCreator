# ProcessPDFImageCreator

ProcessWire module to automatically generate images from all the pages of an uploaded PDF

## Usage

Create an multiple images field called "pdf_images"
Create a files field called "document_pdf"

When you upload a PDF to a page with a template that contains both these fields and save the page, an image will be created and stored for each page of the PDF.

WARNING: the generation process can be quite slow - up to a few minutes if the PDF has 10s to 100s of pages.



## How to install

Your server must have imagemagick, ghostscript, and the imagick pecl extension installed

Download and place the module folder named "ProcessPDFImageCreator" in: /site/modules/

In the admin control panel, go to Modules. At the bottom of the screen, click the "Check for New Modules" button.

Now scroll to the ProcessPDFImageCreator module and click "Install".


## ToDo

Add a spinner to indicate that the images are being generated, or hook into the file upload process and start the image generation immediately after upload has completed and show a new bar with the progress of image generation.


## Support forum
http://processwire.com/talk/topic/3304-pdf-image-generator/


## License

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.

(See included LICENSE file for full license text.)
