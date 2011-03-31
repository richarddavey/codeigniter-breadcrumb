# CodeIgniter-Breadcrumb

CodeIgniter-Breadcrumb is a library that helps your build HTML breadcrumbs with CodeIgniter.


## Requirements

* CodeIgniter 2.0.x


## Example

	// load libary
	$this->load->library('breadcrumb');
	
	// add breadcrumbs
	$this->breadcrumb->appendCrumb('Home', '/');
	$this->breadcrumb->appendCrumb('Page', '/page');
	
	// put this line in view to output
	$this->breadcrumb->output();