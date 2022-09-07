# solidity-file //student details:

// SPDX-License-Identifier: MIT

  pragma solidity ^0.8.0;
 
  
  
  contract studet {
    
      uint id;
      uint age;
      string name;

     function add1stu(uint _id,uint _age,string memory _name) public {
               id =_id;
               age =_age;
               name =_name;
        }
     function getstudet() public view returns(uint,uint,string memory) {
          return(id,age,name);
     }   
     function updatestu(uint _id) public  {
         id=_id;
     }
     
 }
