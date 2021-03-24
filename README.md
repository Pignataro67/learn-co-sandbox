<!--import React, { Component } from 'react',-->

<!--class StudentForm extends Component {-->
<!--  constructor(props) {-->
<!--    super(props)-->

<!--    const { Student } = this.props-->

<!--    this.state = {-->
<!--      id: student ? videoGame.id : null,-->
<!--      name: student ? student.name : '',-->
<!--    }-->
<!--  }-->
  
<!--  class StudentList extends React.Component {-->
<!--  constructor(props) {-->
<!--    super(props)-->

<!--    this.state = { students: this.props.students } //making copy of props storing state-->
<!--  }-->
  
<!--  renderStudents() {-->
<!--    // console.log(this.props.students);-->
<!--    // only show students with more than 6 characters in the name-->
<!--    return this.state.studentsArray.filter(name => name.length > 6 -->
<!--    ).map((student, i) => -->
<!--    <StudentCard key={i} student={student} />-->
<!--    )-->
<!--  }-->

var students = [
   'Doug',
   'Albert',
   'John',
   'Pat',
   'Cathy',
   'Zac',
   'Brad'
  ]

var students = [
  name: 'Doug',
  name: 'Albert',
  name: 'John',
  name: 'Pat',
  name: 'Cathy',
  name: 'Zac',
  name: 'Brad'
  ]
  
  mapFilter1 = students.name.filter(name => name.length > 3).map(name => name + '1')
  
  console.log(mapFilter1);
  
var array1 = [2, 3, 6, 8, 10]

map1 = array1.filter(num => num < 6).map(num => num * num)

console.log(map1)