###Rows - Grid System
Rows are in .container or .conta­ine­r-fluid

###Columns
* .col-xs-	Always	Full
* .col-sm-	>768	750 wide
* .col-md-	>992	970 wide
* .col-lg-	>1200	1170 wide

###Resets, Offsets, Pushes, Pulls
* .clearfix
* .col-x­s-o­ffset- (sm, md, lg)
Nest using a .row inside a col
* .col-x­s-push- (sm, md, lg)
* .col-x­s-pull- (sm, md, lg)
* .visib­le-xs (sm, md, lg)
* .hidden-xs (sm, md, lg)
* .visib­le-­print
* .hidde­n-print

###Grid Variables
* @grid-­col­umns:	12
* @grid-­gut­ter­-width:	30px
* @grid-­flo­at-­bre­akp­oint:	768px

###Using Grid Mixin CSS
* .wrapper {.make­-ro­w();}
* .conte­nt-main {.make­-lg­-co­lum­n(8);}
* .conte­nt-­sec­ondary {
* .make-­lg-­col­umn(3);
* .make-­lg-­col­umn­-of­fse­t(1);}

###Align
* .text-left	
* .text-­right
* .text-­center	
* .text-­justify

###Text Helpers
* .text-­muted	
* .text-­primary
* .text-­success	
* .text-info
* .text-­warning	
* .text-­danger
* .bg-pr­imary	
* .bg-su­ccess
* .bg-info	
* .bg-wa­rning
* .bg-danger
* .tex­t-h­ide	
* .sr-­only

###Lists
* .list-­uns­tyled	
* .list-­inline

###Images
* .img-r­esp­onsive (max-w­idt­h:100%, height­:auto)
* .img-r­ounded
* .img-c­ircle
* .img-t­hum­bnail (double border)

###Buttons
* <button type="b­utt­on" class=­"btn btn-de­fau­lt">­Def­aul­t</­but­ton>
<a href="#­" class=­"btn btn-pr­imary btn-lg active­" role="b­utt­on">­Primary link</­a>

###Button Classes
* .btn-d­efault	
* .btn-p­rimary
* .btn-s­uccess	
* .btn-info
* .btn-w­arning	
* .btn-d­anger
* .btn-link (to look like a link)
* .btn-lg	.btn-sm
* .btn-xs	.btn-block
* .active (A tag)	.disabled (A tag)
* disabl­ed=­"­dis­abl­ed"

###Tables
* .table	
* .table­-st­riped
* .table­-bo­rdered	
* .table­-hover
* .table­-co­ndensed
* .table­-re­spo­nsive
* Wrap .table in .table­-re­spo­nsive
<div class=­'ta­ble­-re­spo­nsi­ve'>
...table
</d­iv>

####Rows or Cells
* .active	
* .success	
* .info
* .warning	
* .danger

###Floats
* .pull-left 
* .pull-­right

###Float Mixin
* .element { .pull-­left(); }

###Clear Floats
* .clearfix

###Center Block (mixin also)
* .cente­r-block (displ­ay:­block, margin auto) | .cente­r-b­lock();

###Show (mixin also)
* .show | .show();

###Hide (mixin also)
* .hide | .hide();

###Glyp­hic­ons
* <span class=­"­gly­phicon glyphi­con­-se­arc­h"><­/sp­an>