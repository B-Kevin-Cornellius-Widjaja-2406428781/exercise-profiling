

## Performance Testing

Screenshot of the performance testings:
1. test_plan_1.jmx (all-student)
![test_1_gui](./assets/images/test_plan_all_student.png)
![test_1_cli](./assets/images/test_plan_all_student_jtl.png)

2. test_plan_1_highest_gpa.jmx (highest-gpa)
![test_1_highest_gpa_gui](./assets/images/test_plan_highest_gpa.png)
![test_1_highest_gpa_cli](./assets/images/test_plan_highest_gpa_jtl.png)

3. test_plan_1_all_student_name.jmx (all-student-name)
![test_1_all_student_name_gui](./assets/images/test_plan_all_student_name.png)
![test_1_all_student_name_cli](./assets/images/test_plan_all_student_name_jtl.png)

## Profiling & Optimization

1. **/all-student (optimizing getAllStudentWithCourse)**

Comparison before and after optimization:
![all-student-optimized](./assets/images/get_all_student_comparison_optimization.png)

2. **/highest-gpa (optimizing findStudentWithHighestGpa)**

Comparison before and after optimization:
![highest-gpa-optimized](./assets/images/get_highest_gpa_comparison_optimization.png)

3. **/all-student-name (optimizing joinStudentNames)**

Comparison before and after optimization:
![all-student-name-optimized](./assets/images/get_all_student_name_comparison_optimization.png)


## Is there an improvement from JMeter measurements?

Ya, tentu saja ada peningkatan performa yang signifikan setelah melakukan optimasi pada ketiga endpoint tersebut. Sebelum optimasi, ketiga endpoint mengalami waktu respon yang cukup lama, terutama pada endpoint `/all-student`. Setelah optimasi, waktu respon untuk ketiga endpoint tersebut berhasil dikurangi secara drastis. Hal ini menunjukkan bahwa optimasi yang dilakukan berhasil meningkatkan performa aplikasi secara keseluruhan, dan memberikan pengalaman pengguna yang lebih baik.