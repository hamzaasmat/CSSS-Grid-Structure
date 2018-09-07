# CSSS-Grid-Structure
Use css grids to make your site more flexible.


/*
-------------------
default grid system
-------------------
*/

.container{
	width: 100%;
}
.container-fluid{
	width: 100%;
}
.row{
	display: flex;
	flex-direction: column;
}
.col-1,.col-2,.col-3,.col-4,.col-5,.col-6,.col-7,.col-8,.col-9,.col-10,.col-11,.col-12{
	margin: .3em;
	padding: .3em;
	position: relative;
}
.col-1 { flex-basis: 8.33%; }
.col-2 { flex-basis: 16.66% }
.col-3 { flex-basis: 25% }
.col-4 { flex-basis: 33.33% }
.col-5 { flex-basis: 41.66% }
.col-6 { flex-basis: 50% }
.col-7 { flex-basis: 58.33% }
.col-8 { flex-basis: 66.66% }
.col-9 { flex-basis: 75% }
.col-10 { flex-basis: 83.33% }
.col-11 { flex-basis: 91.66% }
.col-12 { flex-basis: 100% }

/*offsets*/
.col-offset-1 { margin-left: 8.33%; }
.col-offset-2 { margin-left: 16.66% }
.col-offset-3 { margin-left: 25% }
.col-offset-4 { margin-left: 33.33% }
.col-offset-5 { margin-left: 41.66% }
.col-offset-6 { margin-left: 50% }
.col-offset-7 { margin-left: 58.33% }
.col-offset-8 { margin-left: 66.66% }
.col-offset-9 { margin-left: 75% }
.col-offset-10 { margin-left: 83.33% }
.col-offset-11 { margin-left: 91.66% }
.col-offset-12 { margin-left: 100% }


@media screen and (min-width: 800px){
	.row { display: flex; flex-direction: row; position: relative; }
	.container { width: 1200px; margin: 0 auto; position: relative; }
	.container-fluid { width: 98%; margin: 0 auto; position: relative; }
}
@media screen and (max-width: 1199px){
	.container { width: 100%; }
	.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1,.col-offset-1{
		margin: 0 !important;
	}
}
