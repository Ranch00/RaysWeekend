cmake_minimum_required(VERSION 3.28)

project(RaysWeekend)

add_executable(inOneWeekend)

target_sources(inOneWeekend
    PRIVATE
        src/main.cpp
        src/vec3.h
        src/color.h
        src/ray.h
        src/hittable.h
        src/sphere.h
        src/hittable_list.h
        src/raytracer.h
        src/interval.h
)
