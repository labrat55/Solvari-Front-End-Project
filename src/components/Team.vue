<template>

    <div class="container">
       <div class="col-md-12 text-center">
        <header>
            <h1>Meet the Solvateers</h1>
            <input class="search" type="text" v-model="search" placeholder="Filter by Name or Department">
        </header>
        </div>
 

        <div class="row">

            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1509008364\/production\/images\/nl-NL\/user\/2646" alt="employee-d">
                <div> Name: <span class="title">{{team[3].first_name}}  {{team[3].last_name}}<a href="https://www.linkedin.com/in/dennis-van-den-bos-63850a12/" target="_blank"><i class="fab fa-linkedin"></i></a> </span></div>

                <div> Function: <span class="title">{{team[3].function}}</span></div>


            </div>

            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1508935191\/production\/images\/nl-NL\/user\/3667" alt="employee-d">
                <div> Name: <span class="title">{{team[0].first_name}}  {{team[0].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[0].department}}</span> </div>
                <div> Function: <span class="title">{{team[0].function}}</span></div>

            </div>
             <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1509008489\/production\/images\/nl-NL\/user\/1018" alt="employee-d">
                <div> Name: <span class="title">{{team[8].first_name}}  {{team[8].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[8].department}}</span> </div>
                <div> Function: <span class="title">{{team[8].function}}</span></div>
            </div>
        </div>
         <div class="row">
            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1508936366\/production\/images\/nl-NL\/user\/31029" alt="employee-d">
                <div> Name: <span class="title">{{team[2].first_name}}  {{team[2].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[2].department}}</span> </div>
                <div> Function: <span class="title">{{team[2].function}}</span></div>
            </div>

            <div class="col-md-4">
                <img class="avatar" src="../assets/male.svg" alt="employee-d">
                <div> Name: <span class="title">{{team[4].first_name}}  {{team[4].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[4].department}}</span> </div>
                <div> Function: <span class="title">{{team[4].function}}</span></div>
            </div>
            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1511376756\/production\/images\/nl-NL\/user\/95605" alt="employee-d">
                <div> Name: <span class="title">{{team[1].first_name}}  {{team[1].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[1].department}}</span> </div>
                <div> Function: <span class="title">{{team[1].function}}</span></div>
            </div>
        </div>
        <!-- end row -->
        <!-- Second row with three equal columns-->
        <div class="row">
            <div class="col-md-4">
                <img class="avatar" src="../assets/male.svg" alt="employee-d">
                <div> Name: <span class="title">{{team[5].first_name}}  {{team[5].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[5].department}}</span> </div>
                <div> Function: <span class="title">{{team[5].function}}</span></div>
            </div>
            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1509008265\/production\/images\/nl-NL\/user\/71814" alt="employee-d">
                <div> Name: <span class="title">{{team[6].first_name}}  {{team[6].last_name}}</span> </div>
                <div> Department: <span class="title">{{team[6].department}}</span> </div>
                <div> Function: <span class="title">{{team[6].function}}</span></div>
            </div>
            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1508937626\/production\/images\/nl-NL\/user\/1035" alt="employee-d">
                <div> Name: <span class="title">{{team[7].first_name}}  {{team[7].last_name}} <a href="https://www.linkedin.com/in/gilberto-boekhout-11978b7b/"><i class="fab fa-linkedin"></i></a></span>
                </div>
                <div> Department: <span class="title">{{team[7].department}}</span> </div>
                <div> Function: <span class="title">{{team[7].function}}</span></div>
              
            </div>
        </div>
        <!-- end row -->
        <div class="row">
           
            <div class="col-md-4">
                <img class="avatar" src="../assets/female.svg" alt="employee-d">
                <div> Name: <span class="title">{{team[9].first_name}}  {{team[9].last_name}} <a href="https://www.linkedin.com/in/lennekedegroot/" target="blank"><i class="fab fa-linkedin"></i></a></span> </div>
                <div> Department: <span class="title">{{team[9].department}}</span> </div>
                <div> Function: <span class="title">{{team[9].function}}</span></div>
                </span>
               
            </div>
            <div class="col-md-4">
                <img class="avatar" src="https:\/\/res.cloudinary.com\/solvari\/image\/upload\/c_thumb%2Cf_auto\/v1509008729\/production\/images\/nl-NL\/user\/18929" alt="employee-d">
                <div> Name: <span class="title">{{team[10].first_name}}  {{team[10].last_name}}</span></div>
                <div> Department: <span class="title">{{team[10].department}}</span> </div>
                <div> Function: <span class="title">{{team[10].function}}</span></div>
                <div> LinkedIn: <span class="title">{{team[10].linkedin_url}}</span>
            </div>
        </div>
       
  </div>
  </div>
  
 
</template>

<script>
 
    import axios from 'axios'
  
    export default {
      name: 'Team',
      data() {
        return {
          team: [],
          search: ''
        }
      },
      methods: {
  
      },
      computed: {
        filteredTeams() {
          return this.team.filter(teams => {
            return teams.first_nametoLowerCase().indexOf(this.search.toLowerCase()) > -1 || teams.department.toLowerCase().indexOf(this.search.toLowerCase()) > -1
          })
        }
      },
  
      created() {
        axios.get('https://cors-anywhere.herokuapp.com/https://api.solvari.nl/team.json')
          .then(response => {
            console.log(response)
            this.team = response.data
          }).catch(err => {
            console.log(err)
          })
      }
    }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  
.search{
    margin: 40px 0px 60px 0px;
    width: 340px;
    height: 50px;
    border: 1px solid #585553;
    border-radius: 5px;
    text-align: center;
     margin-top: 0px;
    
}
  .title{
   color:#0479C6; 
}
  
.avatar {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    align-content: center;
    margin-bottom: 20px;
}
  h1{
    margin-top:0px;
    margin-bottom: 60px;
  }
  .row {
    margin-left: 40px;
  }
/*
  i{
    color: #0479C6;
    width: 80px;
    height: 80px;
}
*/
.row {
    margin-bottom: 40px;
    margin-left: 40px
}
  
  /* Small tablets to big tablet: from 768px to 1023px */
@media only screen and (max-width: 1023px){
      header img{
    width: 280px;
    height: 100px;
    margin-bottom: 20px;
    margin-left: 60px;
   
       
    }
    
h1{
    text-align: center;
    font-size: 2.4rem;
    
  margin-left: 0px;

}

.search{
    margin: 0px 0px 40px 0px;
    width: 340px;
    height: 50px;
    border: 1px solid #585553;
    border-radius: 5px;
    text-align: center;
      margin-right: 20px;
    
}
.avatar {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    align-content: center;
    margin-bottom: 20px;
}


.row {
    margin-bottom: 40px;
 margin-left:0px;

 
}
}

/* Small phones to small tablets 481px to 767px */
@media only screen and (max-width: 768px)and (orientation: landscape) {
  header img{
    width: 280px;
    height: 100px;
    margin-bottom: 20px;
    margin-left: 60px;
   
       
    }
    
h1{
    text-align: center;
    font-size: 2.4rem;
  margin-left: 0px;

}

.search{
    margin: 0px 0px 40px 0px;
    width: 340px;
    height: 50px;
    border: 1px solid #585553;
    border-radius: 5px;
    text-align: center;
      margin-right: 20px;
    
}
.avatar {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    align-content: center;
    margin-bottom: 20px;
}


.row {
    margin-bottom: 40px;
     margin-left: 120px;
 
}
    
}

/* Small phones: from 0 to 480px */
@media only screen
and (min-device-width : 320px)
and (max-device-width : 480px) {


   header img{
    width: 280px;
    height: 100px;
    margin-bottom: 20px;
    margin-left: 60px;
   
       
    }
    
h1{
    text-align: center;
    font-size: 2.4rem;
  
  margin-left: 0px;

}

.search{
    margin: 0px 0px 40px 0px;
    width: 340px;
    height: 50px;
    border: 1px solid #585553;
    border-radius: 5px;
    text-align: center;
      margin-left: 34px;
    
}
.avatar {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    align-content: center;
    margin-bottom: 20px;
}


.row {
    margin-bottom: 40px;
     margin-left: 70px;
 
}
     
}

</style>
