# bootstrap-modal-progressbar
a simple progresbar in modal window

Usage 

open: modalProgressBar.show();

hide: modalProgressBar.hide();

options: modalProgressBar.show("waiting ...", {
                dialogSize: 'sm',
                progressType: 'success',
                onHide: function(){
                    alert('done');
                }
});

