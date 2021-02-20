# Tuesday Feb-22-2021 Dotnet WbAPI's > Relationships


## 1. What is the difference between a primary key and a foreign key?

Primary keys are what uniquely identify the object on a table. The foreign key is it's "parent" for lack of a better word, the thing that it is related to and a dependent of 

## 2. What is an Alias?

It's used for longer namespaces or classes. You would do this in the place you want to use it and it would only be contained in that space. It's so you don't have to long hand super long namespaces or classes and instead can call it by an 'Alias' or nickname. 

## 3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections: 

<!-- CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
) -->

string sql = @"
SELECT 
r.*, 
docs.*
FROM patients r
JOIN doctors docs ON r.docId = docs.id
WHERE docId = @id;";

return _db.Query<Patients, Doctors, Patients>(sql (pateints, doctors)=> 
{
    patient.Doctor = doctor;
    return patient;
}, new { id }, splitOn:"id");
}
"


