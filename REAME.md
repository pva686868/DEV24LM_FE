<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content=" width=device-width, initial-scale=1.0">
    <title> vòng lặp</title>
</head>
<body>
    <script>
        //Vòng lặp for
        //Systax:
        //for(giá_trị_khởi_đầu; mệnh_đề_điều_kiện; biến_tăng/biến giảm){
        // các_khối_lệnh
        // }
        for(var i =0;i<10; i++){
            document.write(i+"<br/>");
        }

        //vòng lặp do while
        //Systax:
        //do{
        //các_khối_lệnh
        //}while(mệnh_đề_điều_kiện)
        document.write("do while <br/>");
        var dem=3;
        do{
            document.write(dem+ "<br/>");
            dem++;
        } while(dem<3)
        //vòng lặp while
        //systax:
        //while(mệnh_đề_dk){
        //Các_khoi_lenh
        //       }
        dem =3;
        document.write ("while <br/>")
        while(dem<3){
            document.write(dem+ "<br/>");
            dem++;

        }

        //Array
        var arr= ["dev","vũ ngọc phan", 78, true];
        //object
        var obj ={
            name: " dev",
            address: "25 vũ ngọc Phan",
            age:18
        }
        //for in
        for(var i in obj){
            document.write(obj[i]+"<br/>");
        }
        for(var i in arr){
            document.write(arr[i]+"<br/>");

        }
    
    
    </script>   
</body>
</html>