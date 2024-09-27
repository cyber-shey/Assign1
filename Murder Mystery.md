SELECT* FROM crime_scene_report LIMIT 5;
![image](https://github.com/user-attachments/assets/d6f2e725-c478-462f-97a5-330d9e7bf3a5)


SELECT *
FROM crime_scene_report
WHERE type = "murder";
![image](https://github.com/user-attachments/assets/f3cf2a9c-0545-4f5d-a009-0bceeb82bf8b)


SELECT *
FROM crime_scene_report
WHERE type = "murder"
AND date = 20180115
AND city = "SQL City";
![image](https://github.com/user-attachments/assets/02fe6f06-6602-4c15-a992-ddeb0b0f748b)


SELECT *
FROM person
LIMIT 5;
![image](https://github.com/user-attachments/assets/daf11cb0-f302-4408-96d7-c5d9222df6a9)


SELECT *
FROM person
WHERE address_street_name = "Northwestern Dr"
ORDER BY address_number DESC;
![image](https://github.com/user-attachments/assets/6b0f9678-e133-43e5-b34d-33c229cab8ab)


SELECT *
FROM person
WHERE name LIKE '%Annabel%'
AND address_street_name = "Franklin Ave";
![image](https://github.com/user-attachments/assets/f88d7f72-617f-4d7a-a822-d39aa8998644)


SELECT *
FROM interview
WHERE person_id IN ("14887", "16371");
![image](https://github.com/user-attachments/assets/57cce068-d828-4a05-8bd3-8f928fbe5647)


SELECT *
FROM get_fit_now_check_in
WHERE membership_id LIKE '48Z%'
AND check_in_date = "20180109";
![image](https://github.com/user-attachments/assets/852a1cb1-5a1b-4a69-ab18-5bca9324903a)


SELECT *
FROM drivers_license
WHERE gender = "male"
AND plate_number LIKE '%H42W%';
![image](https://github.com/user-attachments/assets/e6badbb6-60b8-4ad8-b23e-488e5e5cc0cb)


SELECT *
FROM person
WHERE license_id IN ("423327", "664760");
![image](https://github.com/user-attachments/assets/b615c162-eba9-4210-8ef0-3b78e4bd5caf)


SELECT *
FROM get_fit_now_member
WHERE person_id IN ("51739", "67318");
![image](https://github.com/user-attachments/assets/d415fb70-4737-43d9-8dc5-ea51120ca8d8)


INSERT INTO solution VALUES (1, 'Jeremy Bowers');
SELECT value FROM solution;
![image](https://github.com/user-attachments/assets/e0090c0a-3e36-4afe-90f7-9e952ef7546a)


