# package com.example.teacherdashboard;

import java.util.ArrayList;
import java.util.List;

public class TeacherDAO {
    private static List<Teacher> teachers = new ArrayList<>();

    static {
        teachers.add(new Teacher("John Doe"));
        teachers.add(new Teacher("Jane Smith"));
    }

    public List<Teacher> getTeachers() {
        return teachers;
    }
}
