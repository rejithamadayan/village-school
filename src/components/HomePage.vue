<template>
  <div class="home-page">
    <div class="home-page__top-sec">
      <div class="home-page__header">
        <h4 >Gulshan EverGreen Children’s Academy &amp; Junior High School</h4>
        <p>@Village Baksar, Basti, Uttar Pradesh, India</p>
      </div>
     
    </div>
    <div class="carousel-container">
      <h4 class="carousel-header">WELCOME TO GES SCHOOL Buxar Basti</h4>
      <div  class="carousel-sec">
        <div class="disctiption-sec__item">
        <h4>ABOUT</h4>
        <p>
          A promising education institution dedicated for betterment of Society by spreading education to
          rural areas and remote villages in India.<br>
          School is established in 2005 and embarked to provide primary education irrespective of caste,
          creed, religion or socio-economic background and providing quality education to the children of the
          village especially from the rural areas.
          OUR endeavour IS to encourage the future generation from remote villages to excel in the field of
          education and general life and to make them a responsible and committed citizen of future India.<br>
          Our main focus is to motivate all sections of society to get educated and especially ensuring that
          village Girl children complete their primary education and motivate them for higher studies.<br>
          The school has started junior high school in year 2019
        </p>
      </div>
        <b-carousel
        :interval="2500"
      >
        <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
          <!-- <b-image class="image" :src="carousel.url"></b-image> -->
            <img :src="carousel.url" alt=""> 
        </b-carousel-item>
      </b-carousel>
      <div class="disctiption-sec__item">
        <h4>VISION & MISSION</h4>
        <p>
         GES taking steps to bring world class education to every child from Village for their better future
         GES working toward holistic development of every student making them future ready.
         Transforming lives and creating future leaders using technology.

        </p>
      </div>
      </div>
      
    </div>
    <div class="home-page__disctiption-sec">
      <div class="disctiption-sec__item">
        <h4>Location</h4>
        <p>
          The school is located at village Baksar of district Basti in Uttar Pradesh, India.
          School is situated on the way side, in the midst of mango tree precincts, surrounded by agriculture fields. It is a perfect ambience for children to learn and enjoy nature. 
        </p>
      </div>
      <div class="disctiption-sec__item">
        <h4>Approach to Education </h4>
        <p>
          The school has employed high standard teaching methodologies where teachers give personal attention to each student. The school focuses more on personality development by imbibing moral values in children and it is a part of standard curriculum.<br>
          To keep pace with modern education, Computer education has been introduced at primary level.
          GES Trust cares for society and hence provides fee concession to needy and poor children. Provide special concessions for girl education.<br>
          GES Trust encourages school-drop out to pursue their incomplete education.<br>
          The school is also planning to start Special classes to teach guardians and elders under “Proad shiksha Abhiyan”.

        </p>
      </div>
      <div class="disctiption-sec__item">
        <h4>Library and Laboratory </h4>
        <p>
          School library has a range of books from General knowledge to Computers. <br>
          In the coming year, a separate Computer laboratory and Science laboratory is being built for primary and secondary level students.
        </p>
      </div>
      <div class="disctiption-sec__item">
        <h4>FUTURE Educational Programs  </h4>
        <p>
          <ul>
            <li>
              Vocational Education – Starting up industrial oriented courses
              <ul>
                <li>
                  Tailoring Classes
                </li>
                <li>
                  Art and Handicraft Classes
                </li>
              </ul>
            </li>
            <li>Distance Education program - NIOS</li>
          </ul>
        </p>
      </div>
    </div>
    <div class="home-page__staffs">
      <h4>Staffs</h4>
      <p>All teachers are well qualified, trained, motivated and dedicated to empower the children to excel in education and face challenges in all fields.</p>
      <div class="staffs">
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Niraj Singh</p>
            <h4>Principal, M.A.(English)</h4>
          </div>
        </div><div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Farida Ansari</p>
            <h4>Vice Principal, M.A. (Urdu), B.Ed Mumbai</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Ram Boazh Yadav</p>
            <h4>Teacher, B.A.</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Akthar Hussain Ansari</p>
            <h4>Teacher, B.Com</h4>
          </div>
         
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Adeep Rawat</p>
            <h4>Teacher, B.A.</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Miss Ankita Pandey</p>
            <h4>Teacher, M.A. (Sociology)</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Ejaz Ansari</p>
            <h4>Teacher, Computer Laboratory Assistant (B.Com., PGDCA(Computers))</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Abdul Kadir Ansari</p>
            <h4>Teacher, B.Sc. (Maths)</h4>
          </div>
          
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>RamBali Gupta</p>
          <h4>Teacher, B.A.</h4>
          </div>
        </div>
        <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>

          <div>
            <p>Inshaan Ali Ansari</p>
          <h4>Administrative Staff, M.Com. – Chief Administrator</h4>
          </div>
        </div>
         <div>
          <div><img src="../assets/avatar.jpg" alt=""></div>
          <div>
            <p>Shamim Ansari</p>
          <h4>Librarian, B.A.</h4>
          </div>
        </div>
      </div>
    </div>
    <div class="home-page__trust">
      <h4>Contribution to School Trust</h4>
      <p>
        Gulshan Evergreen school trust is working toward upliftment of people's lives in remote villages by imparting quality and high standard education to poor and downtrodden children in our remote villages. 
        On behalf of School trust, you are also invited to chip in your contribution and feel the joy of giving back to Society by working together with us to achieve a common goal by spreading education to under-privileged and poor village children. 
      </p>
      <div>
        <h4><b>You can contribute in following form:</b></h4>
        <ul>
          <li>
            Do charity by donating a sum to build part of the school, a classroom in memory of your loved ones, building library rooms, laboratory rooms.
          </li>
          <li>Sponsor for Computers, sports kits for children.</li>
          <li>Sponsor a child for a year by taking care of fees.</li>
          <li>The institution has applied for registration at state level as Charitable trust that will entitle donation Income tax rebate under 80G - 1324/2002-2003 under the Indian Income Tax Act 12(A)/2002-2003</li>
        </ul>
      </div>
      <div>
        <h4><b>Various Payment Options are as given below:</b> </h4>
        <div>
          <p>By Cheque/DD/Money Order </p>
          <p><b>Send your contribution by Cheque/DD/MO in favour of “Gulshan Evergreen School Trust” and forward it at below address.</b> </p>
        <p>
          The Principal<br>
          Gulshan EverGreen School<br>
          Baksar Village, District Basti,<br>
          State Uttar Pradesh, India
        </p>
        </div>
      </div>
    </div>
    <div class="home-page__staffs">
      <h4>Trust Members</h4>
      <b-table :data="trustList" :columns="columns" bordered></b-table>
    </div>
    <div class="home-page__admission">
      <h4>Better Future Begins with quality education at GES School</h4>
     <div>
        <b-field label="Name">
            <b-input v-model="name" placeHolder="Enter name"></b-input>
        </b-field>
        <b-field label="Phonenumber">
            <b-input v-model="phone" placeHolder="Phone number"></b-input>
        </b-field>
        <b-field label="Email ID">
            <b-input v-model="email" placeHolder="Enter email"></b-input>
        </b-field>
        <b-field label="Select City">
            <b-select placeholder="Select a city" expanded size="is-small">
                <option>
                  City A
                </option>
                <option>
                  City b
                </option>
                <option>
                  City A
                </option>
            </b-select>
        </b-field>
         <b-field label="Select Campus">
            <b-select placeholder="Select a Campus" expanded size="is-small">
                <option>
                  Campus A
                </option>
                <option>
                  Campus b
                </option>
                <option>
                  Campus A
                </option>
            </b-select>
        </b-field>
         <b-field label="Select Grade">
            <b-select placeholder="Select a grade" expanded size="is-small">
                <option>
                  Grade A
                </option>
                <option>
                  Grade b
                </option>
                <option>
                  Grade A
                </option>
            </b-select>
        </b-field>
     </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      carousels: [
        {
          url: require("../assets/home.png"),
        },
        {
          url: require("../assets/home2.png"),
        },
        {
          url: require("../assets/home3.png"),
        },
        {
          url: require("../assets/home4.png"),
        },
        {
          url: require("../assets/home5.png"),
        },

        {
          url: require("../assets/home6.png"),
        },
        {
          url: require("../assets/home7.png"),
        },
        {
          url: require("../assets/home8.png"),
        },
        {
          url: require("../assets/home9.png"),
        },
      ],
      trustList: [
        {
          name: "Mr. Abu Bakr Ansari",
          position: "President",
          qualification: "DIO, Basti, Uttar Pradesh",
        },
        {
          name: "Sir (Lecturer) Jamaluddin",
          position: "Vice President",
          qualification:
            "Vice-Principal, Khair Inter College, Basti, Uttar Pradesh",
        },
        {
          name: "Akthar Hussain Ansari",
          position: "Manager",
          qualification: "DIO, Basti, Uttar Pradesh",
        },
        {
          name: "Inshaan Ali (Ehsan Ali) Ansari",
          position: "Deputy Manager (Finance)",
          qualification: "Manager (Retired), UP Handlooms, Uttar Pradesh",
        },
        {
          name: "Azmat Ali Ansari",
          position: "Manager (Administration)",
          qualification:
            "Foreman (Retired), Mechanical Dept., I.I.T.-Powai, Mumbai-76, Maharastra",
        },
        {
          name: "Abdul Kadir Ansari",
          position: "Auditor",
          qualification: "",
        },
        {
          name: "Khairat Ali Ansari",
          position: "Member",
          qualification: "",
        },
        {
          name: "Karimullah Ansari",
          position: "Member",
          qualification: "",
        },
        {
          name: "Abdul Wahab Ansari",
          position: "Member",
          qualification: "",
        },
        {
          name: "Dr. Imtiyaz Javed Ansari",
          position: "Member",
          qualification: "",
        },
        {
          name: "Ashgar Ali Ansari",
          position: "Member",
          qualification: "",
        },
      ],
      columns: [
        {
          field: "name",
          label: "Name",
        },
        {
          field: "position",
          label: "Position",
        },
        {
          field: "qualification",
          label: "Qualification",
        },
      ],
    };
  },
};
</script>
<style lang="scss" >
.table {
  margin-top: 16px;
  background-color: #d3efef !important;
  thead {
    background-color: #efc9c9 !important;
    font-size: 14px;
  }
  tbody {
    font-size: 12px;
  }
}
.carousel-container {
  margin: 0 32px;
  img {
    height: 400px;
    width: 100%;
    object-fit: cover;
  }
  .carousel-header {
    padding: 16px 0;
    font-weight: 600;
    font-size: 18px;
  }
  .carousel-sec {
    display: flex;
    flex: 0;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    border-radius: 6px;
    overflow: auto;
    padding: 16px 0 16px 16px;
    > div {
      flex-basis: 0;
      flex-grow: 1;
      margin-right: 16px;
      // background-color: #d1ede5;
      background-color: #d3efef;

      border-radius: 6px;
      padding: 8px 16px;
      overflow: auto;
      box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px,
        rgba(0, 0, 0, 0.23) 0px 3px 6px;
    }
    > div:nth-child(2) {
      padding: 0;
    }
  }
  .disctiption-sec__item {
    h4 {
      font-size: 18px;
      font-weight: 600;
      margin-bottom: 8px;
      text-shadow: 0 1px 0 #cccccc, 0 2px 0 #c9c9c9, 0 3px 0 #bbb,
        0 4px 0 #b9b9b9, 0 5px 0 #aaa, 0 6px 1px rgba(0, 0, 0, 0.1),
        0 0 5px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.3),
        0 3px 5px rgba(0, 0, 0, 0.2), 0 5px 10px rgba(0, 0, 0, 0.25),
        0 10px 10px rgba(0, 0, 0, 0.2), 0 20px 20px rgba(0, 0, 0, 0.15);
    }
    p {
      font-size: 14px;
      font-style: oblique;
      font-family: "Material Design Icons";
      color: #000;
    }
    .disctiption-sec__item {
      margin-bottom: 16px;
    }
  }
  .carousel-item {
    margin-bottom: -8px;
  }
}
.home-page__header {
  padding: 16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-self: start;
  h4 {
    color: #000;
    font-size: 32px;
    text-shadow: 0 1px #808d93, -1px 0 #cdd2d5, -1px 2px #808d93,
      -2px 1px #cdd2d5, -2px 3px #808d93, -3px 2px #cdd2d5, -3px 4px #808d93,
      -4px 3px #cdd2d5, -4px 5px #808d93, -5px 4px #cdd2d5, -5px 6px #808d93,
      -6px 5px #cdd2d5, -6px 7px #808d93, -7px 6px #cdd2d5, -7px 8px #808d93,
      -8px 7px #cdd2d5;
  }
  p {
    color: #000;
    font-size: 14px;
    text-shadow: 1px 0px 1px #ccc, 0px 1px 1px #eee, 2px 1px 1px #ccc,
      1px 2px 1px #eee, 3px 2px 1px #ccc, 2px 3px 1px #eee, 4px 3px 1px #ccc,
      3px 4px 1px #eee, 5px 4px 1px #ccc, 4px 5px 1px #eee, 6px 5px 1px #ccc,
      5px 6px 1px #eee, 7px 6px 1px #ccc;
    font-style: italic;
  }
}
.home-page__disctiption-sec {
  padding: 16px;
  margin: 16px 30px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 6px;
  display: flex;
  flex-wrap: wrap;
  > .disctiption-sec__item {
    box-shadow: rgba(14, 30, 37, 0.12) 0px 2px 4px 0px,
      rgba(14, 30, 37, 0.32) 0px 2px 16px 0px;
    flex: 1 1 48%;
    margin: 8px;
    padding: 16px;
    border-radius: 6px;
    background: #d3efef;
    h4 {
      font-size: 18px;
      font-weight: 600;
      margin-bottom: 8px;
      text-shadow: 0 1px 0 #cccccc, 0 2px 0 #c9c9c9, 0 3px 0 #bbb,
        0 4px 0 #b9b9b9, 0 5px 0 #aaa, 0 6px 1px rgba(0, 0, 0, 0.1),
        0 0 5px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.3),
        0 3px 5px rgba(0, 0, 0, 0.2), 0 5px 10px rgba(0, 0, 0, 0.25),
        0 10px 10px rgba(0, 0, 0, 0.2), 0 20px 20px rgba(0, 0, 0, 0.15);
    }
    p {
      font-size: 14px;
    }
  }
}
.carousel .carousel-indicator.is-inside.is-bottom {
  bottom: 8px !important;
}
.home-page__admission {
  padding: 16px;
  margin: 16px 30px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 6px;
  h4 {
    margin-bottom: 8px;
  }
  > div {
    border-radius: 6px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    padding: 8px;
    background-color: #d3efef !important;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    // flex-direction: column;
    > div {
      display: flex;
      flex-direction: column;
      flex: 0 0 30%;
    }
    > div > * {
      font-size: 14px !important;
    }
  }
  .input {
    height: 28px !important;
    &::placeholder {
      font-size: 12px !important;
    }
  }
}
.home-page__staffs {
  padding: 16px;
  margin: 16px 30px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 6px;
  h4 {
    font-size: 18px;
    font-weight: 600;
  }
  p {
    font-size: 14px;
    padding-bottom: 8px;
  }
  .staffs {
    display: flex;
    flex-wrap: wrap;
    p {
      font-size: 14px;
      font-weight: 600;
    }
    h4 {
      font-size: 12px;
      font-weight: 500;
    }
    > div {
      display: flex;
      flex-direction: column;
      text-align: center;
      flex: 0 0 15%;
      margin: 8px;
      border-radius: 6px;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2),
        0 6px 20px 0 rgba(0, 0, 0, 0.19);
      padding: 8px;
      background-color: #d3efef !important;
      > * {
        margin-bottom: 6px;
      }
    }
  }
}
.home-page__trust {
  padding: 16px;
  margin: 16px 30px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 6px;
  > h4 {
    font-size: 18px;
    font-weight: 600;
    margin-bottom: 8px;
  }
  > * {
    font-size: 14px;
  }
  > div {
    margin: 16px 0;
    background-color: #d3efef;
    box-shadow: rgba(14, 30, 37, 0.12) 0px 2px 4px 0px,
      rgba(14, 30, 37, 0.32) 0px 2px 16px 0px;
    padding: 16px;
    ul {
      padding: 0 32px;
    }
    ul li {
      list-style-type: decimal;
    }
  }
}
@media only screen and (max-width: 600px) {
  .home-page__header {
    h4 {
      font-size: 18px;
      text-align: center;
    }
  }
  .carousel-header {
    font-size: 14px !important;
  }
  .carousel-sec {
    display: block !important;
    > div {
      margin-bottom: 16px;
    }
  }
  .home-page__staffs {
    .staffs {
      flex-direction: column;
    }
  }
  .table {
    background-color: #fff !important;
    tbody {
      tr {
        background-color: #d3efef !important;
      }
    }
  }
  .home-page__admission {
    > div {
      flex-direction: column;
    }
  }
}
</style>