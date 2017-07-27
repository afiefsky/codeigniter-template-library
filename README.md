# codeigniter-template-library
1. Copy the file into libraries folder inside application folder.
2. Open autoload.php and find libraries.
3. Add 'libraries' into its array.
4. Save.
5. To use it, first make template file inside views folder, and insert and a line <?php echo $contents; ?>.
6. And then, on your controller, instead of using $this->load->view('view_file'), use $this->template->load('your_template_file', 'your_view_file').

