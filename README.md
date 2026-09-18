function drawMap(){
  // رسم أرض أنوال مؤقتا حتى تطلع الصورة
  ctx.fillStyle = "#d2b48c";
  ctx.fillRect(0,0,canvas.width,canvas.height);
  
  // رسم جبال
  ctx.fillStyle = "#8B5A2B";
  ctx.beginPath();
  ctx.moveTo(0,150); ctx.lineTo(100,50); ctx.lineTo(200,150); ctx.fill();
  
  // علم الريف
  ctx.font = "30px Arial";
  ctx.fillText("ⵜⴰⵎⴰⵣⵖⴰ", 150, 200);
}
