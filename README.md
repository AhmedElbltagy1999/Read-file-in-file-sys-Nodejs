const fs =require('fs')
fs.readFile('osama.txt','utf8',(err,file)=>{
        if(err)
        console.log(err);
        else
        console.log(file);
    })
