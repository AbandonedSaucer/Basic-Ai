var Player : Transform;
var MoveSpeed = 4;
var MaxDist = 10;
var MinDist = 5;




function Start ()
{

}

function Update ()
{
    transform.LookAt(Player);
    if(Vector3.Distance(transform.position,Player.position) >= MinDist){
