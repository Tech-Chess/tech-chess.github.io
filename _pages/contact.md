---
layout: inner
title: Contact
permalink: /contact/
---

<p style="text-align: center;" markdown="1">

For sponsorship inquiries please email our finance team at [techess-fin@mit.edu](mailto:techess-fin@mit.edu).

<br><br>

For general inquiries please contact [techess-exec@mit.edu](mailto: techess-exec@mit.edu).

</p>


<p style="text-align:center;" markdown="1">
  <input type="button" id="startBtn" value="Start" />
  <input type="button" id="clearBtn" value="Clear" />
  <div id="board2" style="width: 400px; text-align:center;"></div>
</p>

<script>

var init = function() {

//--- start example JS ---
var board2 = ChessBoard('board2', {
  draggable: true,
  dropOffBoard: 'trash',
  sparePieces: true
});
$('#startBtn').on('click', board2.start);
$('#clearBtn').on('click', board2.clear);
//--- end example JS ---

}; // end init()
$(document).ready(init);
</script>
