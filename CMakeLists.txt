# CMakeList.txt : fichier projet CMake de niveau supérieur, effectuez une configuration globale
# et incluez les sous-projets ici.
#
cmake_minimum_required (VERSION 3.8)

# Solution
project ("SAE921-GRP4100-SFML")

# Each sub-project
set(EXECUTABLE_CUSTOM_NAME "00-Starter")
add_subdirectory ("00-Starter")
