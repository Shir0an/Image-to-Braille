Python prototype:

Dependancies: Pillow
Usage: main.py [filepath] (Optional)[weight]

Some examples:

⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠤⠐⠄⠉⠉⠄⠄⠉⠁⠄⠒⠠⠄⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⠄⠈⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠁⠠⢀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⠔⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠑⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠠⠂⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⢀⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢠⠁⠄⠄⠄⠄⠄⠄⠄⠄⢀⡆⠄⠄⠰⡀⠄⠄⠄⠄⠙⣦⠄⠄⠄⠑⣄⠄⠄⠁⡀⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠆⠄⠄⠄⠄⠄⠄⠄⠄⠄⣾⠄⠄⠄⡄⠖⠄⠄⠄⠄⠄⠸⢷⣄⠄⠄⠸⣆⠄⠄⠐⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡄⠄⠄⠄⢸⡇⠄⠄⠄⠁⢠⡐⡀⠄⠄⠄⠄⢁⢹⣆⠄⠄⢻⡆⠄⠄⠃⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢸⠄⠄⠄⠄⠄⠁⠄⠄⠄⣾⠁⠄⠄⢰⣾⡿⠃⠐⠄⡀⠄⠄⠈⠄⠈⠆⠄⢸⣿⠄⠄⢸⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠄⠄⠄⠄⠄⠄⠄⠄⠄⡟⠄⠄⠄⠎⠉⠄⠄⠄⠄⠃⢀⠄⠄⠃⠄⠈⠄⢸⣿⡇⡇⢀⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡐⡄⠄⠄⠄⡇⡄⠄⠄⠄⠁⠄⠄⡈⠄⠄⠄⢇⠄⠄⠄⠄⠄⠄⠄⢠⡴⣦⢸⣿⣇⠁⠸⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡐⠁⢀⠄⠄⠄⠄⠇⠄⠄⠄⢠⠄⠐⢀⣴⢾⣛⠦⠄⠄⠄⠄⠄⠄⠈⡋⡶⣼⠄⣿⡿⠄⠆⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠠⠊⠄⠄⠸⠄⠄⠄⠘⢀⠄⠄⠄⠈⠌⢀⡟⢡⣁⣏⣷⠄⠄⠄⠄⠄⠄⠄⣿⢿⠏⠠⣿⠃⠠⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠁⠄⠄⠄⠄⢀⠄⠄⠄⠄⢋⠄⠄⠄⠄⠃⠈⠇⢸⣿⣟⡻⠄⠄⠄⠄⠄⠄⠄⠙⠋⠄⠄⠃⠄⠂⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠘⠄⠄⠄⣾⣌⠇⠄⠄⠄⢀⠄⠄⠄⠉⠉⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡈⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠠⢁⠁⠄⣸⣿⣿⣧⠄⠄⠄⠈⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢶⢀⠁⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⠃⠂⠄⣼⣿⣿⣿⣿⠄⠄⠄⢰⠇⠄⠄⠄⠄⠄⠄⠄⠄⠐⢶⠄⠄⠄⢀⡄⢸⡄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣀⠂⢀⣼⣿⣿⣿⣿⣿⡇⠄⠄⣾⡎⠂⢄⠄⠄⠄⠄⠂⠄⠄⠁⠄⣠⣴⣿⠄⠸⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡠⠁⢠⣾⣿⣿⣿⣿⣿⣿⡇⠄⠄⣿⣷⠢⡀⠈⠄⠄⠄⢀⡀⡀⣴⣿⣿⣿⣿⠄⠄⣶⣶⣶⡄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⢀⠔⠄⣰⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⢰⣿⡿⠄⠄⠐⠠⢀⠄⠔⠁⠄⣿⣿⣿⣿⣿⡀⠄⣿⣿⣿⣿⡀⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⡠⠄⢀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⢸⣿⣧⡀⠄⠄⠄⢰⣼⣾⣄⠄⣿⣿⣿⣿⣿⡇⠄⢿⣿⣿⣿⡇⠄⠄⠄⠄
⠄⠄⠄⠄⠄⢀⠄⠄⢠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⣿⣿⣿⣿⣦⠄⢀⣾⣿⢹⣿⣆⣿⣿⣿⣿⣿⣇⠄⢸⣿⣿⣿⣷⠄⠄⠄⠄
⠄⠄⠄⠄⠠⠂⠄⣠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣸⣿⣿⣿⣿⣿⣷⣼⡟⣿⠈⣿⣻⣿⣿⣿⣿⣿⣿⢰⠄⣿⣿⣿⣿⠄⠄⠄⠄
⠄⠄⠄⡰⠁⠄⣰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢀⣿⣿⣿⣿⣿⣿⣿⠿⢱⣿⠄⢻⡧⡏⢿⣿⣿⣿⣿⣿⠄⢸⣿⣿⣿⠄⠄⠄⠄
⠄⠄⠰⠁⠄⣰⣿⣿⣿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⣼⣿⣿⣿⣿⣿⣿⣿⣆⠄⢹⠄⠈⠄⠁⡸⢿⣿⣿⣿⣿⠄⠘⣿⣿⣿⣷⠄⠄⠄
⠄⢀⠁⡀⢠⣿⣿⣿⡟⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⢧⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⢺⠄⠸⠘⡖⠠⠄⠝⠙⣿⣿⠄⠄⣿⣿⣿⣿⡌⠄⠄
⠄⡈⡌⠃⣾⣿⣿⠏⢀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⡿⠿⠟⠛⣼⣇⢠⠈⣷⠐⣠⢀⠠⠁⠁⠄⠄⣿⣿⣿⣿⣗⠈⡄
⠄⡷⠄⢰⣿⡿⠃⣠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠄⠄⠈⠄⢸⣿⣼⣇⠐⠄⠄⠄⠄⠈⠈⣄⡀⣿⣿⣿⣿⣿⠈⢤
⠄⡇⠄⢿⡟⠁⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠝⠁⠄⠄⠄⠄⢀⢸⣿⣿⣿⣄⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⠄⠘
⠄⠄⠄⡘⢠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄⠄⣀⣼⣿⣿⣿⣿⣯⡀⠄⢄⠄⠄⣿⣿⣿⣿⣿⣿⣿⠄⠄
⠄⠄⡐⣠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⡀⠄⠄⠄⣠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣴⣆⣐⢠⣿⣿⣿⣿⣿⣿⣿⡇⠄
⠄⠐⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⠡⢤⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄
⢠⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠁⠄
⣸⡿⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠁⠄⠄⠄
⣿⠁⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡀⠄⠄⠄⠄⠄⠄
⡇⠄⠈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡈⠂⠄⠄⠄⠄
⠇⠄⠄⠘⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⠈⡄⠄⠄⠄

⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣤⣤⣤⣄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣰⣾⣿⣿⣾⣿⣿⠛⣿⡇⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢿⡿⣿⡿⣿⣿⣿⣿⣿⠇⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣰⣷⠄⠄⠄⠄⣤⣶⣾⣿⣿⣷⣶⣤⣄⡀⣀⣴⣾⣷⡿⣿⣿⣿⡏⠉⠁⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢠⣿⣿⡄⣠⣤⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠛⠉⠈⠛⠿⢿⡿⡅⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡀⠄⠄⠄⠄⠹⣷⡋⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠸⣧⡽⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⢀⣀⢀⢠⠁⢀⡀⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⣴⣿⣿⠳⡸⣄⣞⠄⠒⢿⣿⣿⣿
⠄⠄⠄⠄⠄⠄⠄⠄⢀⣤⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣅⠄⡨⡷⡥⡀⠄⡀⠋⠄⠄
⠄⠄⠄⠄⠄⠄⠄⣰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣰⠄⠱⢄⠘⠄⠄⠄⠄
⠄⠄⠄⠄⠄⢀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⡄⢀⣀⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣷⢟⣁⣀⠄⠄⠄⠄
⠄⠄⠄⠄⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢟⣿⣿⣿⣿⠋⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣀⡀⠄
⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⢋⣡⣾⣿⣿⠟⠁⠄⠄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠄⠄
⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⢉⣠⣶⠿⣿⣛⣫⣥⣀⣀⠄⠄⠈⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⠄
⠄⠄⠄⠄⢻⣿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣯⡤⠄⠄⠄⠠⢶⠿⣛⣯⣍⣉⣉⣩⣿⣦⣴⣿⣿⣿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⠁⠄⠄
⠄⠄⠄⠄⠘⣿⣿⣿⣿⣿⣧⣻⣿⣿⣿⣿⣶⡀⠄⠄⣠⡶⢿⣿⣿⣿⣍⠉⠉⢻⣿⠟⠫⢿⣿⣿⣿⣿⣿⣿⡄⣿⣿⣿⣿⣿⠏⠄⠈⠄
⠄⠄⠄⠄⠄⠻⣿⣿⣿⣿⣿⢩⣿⠟⣿⣿⠋⢿⣿⣿⣿⡇⠈⢿⠁⠻⣷⣶⡢⠼⣿⠄⠄⠘⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣟⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⡄⠛⢄⣙⡿⠟⢽⡏⠄⠈⢻⣄⠈⠉⠉⠉⠄⠄⢠⡏⠄⠄⠄⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⠃⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠸⣿⣿⣿⣿⣇⠄⠄⠄⠄⢀⣾⠁⠄⠄⠄⠙⠷⣤⣤⣤⡴⠶⠋⠄⠄⠄⠄⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⢻⣿⣿⣿⣿⠓⠶⠶⠶⠛⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⡿⠁⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⢀⡽⣿⣿⣿⣆⠄⠄⠄⠄⠄⠘⠷⣶⠟⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠙⣻⢿⣿⣿⣦⡀⠄⠄⠄⢀⣀⣀⣀⣀⣀⡠⠄⠄⠄⠄⠄⠄⠄⢀⣤⣿⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠋⠄⠙⢿⣿⣷⣄⡀⠄⠄⠹⡿⠹⠏⠄⠄⠄⠄⠄⠄⠄⠄⣠⣿⡿⣿⣿⣿⡿⠋⠻⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢹⣿⣿⣷⣆⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣼⣿⣿⣿⣿⡿⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠹⣿⣿⣿⣧⡀⠄⡀⠄⠄⠄⠄⢀⣠⣶⣿⢟⡁⣿⡿⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⣹⣿⡟⢿⣄⢿⣶⣶⣶⣾⣿⣿⣯⣾⣿⠟⠉⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣴⣿⣿⣿⣿⣄⠉⠙⣿⣿⣿⣿⣿⣿⡿⠟⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣥⡤⠾⣿⣿⣿⡿⣿⣷⣤⡘⣿⣿⣿⣿⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣠
⠄⠄⠄⠄⠄⠄⡀⠄⠄⠄⠄⠄⢈⠁⠄⢻⣿⣿⣿⣿⣿⣿⣿⣿⡿⠋⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣀⣤⣶⣿
⠄⠄⠄⠄⠄⠄⠄⠄⠂⢠⣀⠄⡚⡄⢀⠾⣿⣿⣿⣿⣿⣿⠟⠉⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢰⣾⡇⣠⣾⣿⣿⣿⣿
⠄⠄⠄⠄⢠⠁⠄⡸⠄⣾⣿⣶⣠⢉⣁⠄⠸⠟⣫⡿⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⠄⠄⠄⣠⣴⣿⣿⣦⡟⣰⣿⣿⣿⣿⣿⣿
⠄⠄⠄⠄⠘⣿⢶⣣⣼⣿⣿⠁⠈⢿⣻⠐⣰⣿⠏⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠐⣄⣴⣿⣶⣶⣿⣿⠘⠛⠛⡟⢠⣿⣿⣿⡿⢛⣽⡝
⠄⠄⠄⠄⠄⢹⣿⣿⣿⣿⡟⠄⠄⢀⠟⣾⣿⡟⠄⡀⠄⠄⠄⠄⠄⠄⢰⣿⣆⣶⣤⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⠃⣼⣿⣿⢟⣷⡟⣩⣶
⠄⣠⡤⢠⠄⢸⣿⣿⣿⣿⠇⠄⠄⢸⠄⣿⣿⣇⣼⣧⢠⣄⣴⣶⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣰⣿⣿⣿⢾⣿⣧⢿⣯
⣰⣿⢧⠏⠄⢸⣿⣿⣿⣿⠄⠄⠄⠸⠐⢺⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡀⠙⣿⣯⣿
⣿⣿⡟⠄⠄⢸⣿⣿⡟⠉⠄⠔⠄⠄⠄⠄⠄⣀⣘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠋⢹⣿⣿⣿⣿⣿⣿⣸⣌⠂⠈⠻⢿
⣿⣿⠁⠄⠄⠄⣿⣿⡷⠂⠄⠄⠄⠄⠄⠘⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣿⠿⠋⠄⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿⣷⢤⡀⠄
⣿⣏⠄⠄⠄⠄⠙⠟⠄⠄⠄⠄⣀⣠⣤⣴⣶⣿⣿⣿⣿⣿⠿⠿⠟⠛⢋⣉⡥⠴⠚⠉⠄⠄⠄⠄⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⠉⠓
⡿⢀⠂⠄⠄⠄⢨⠆⢀⣠⣶⡿⠿⠛⠛⠉⠉⠉⠉⣀⣀⣠⡤⠴⠒⠋⠉⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠸⣿⣿⣿⣿⣿⣿⣿⡇⠈⠛⠄⠄
⣷⠎⠄⠄⠄⠄⠄⡴⠛⠉⣀⣠⣤⢴⣶⠚⠛⠉⠉⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢻⣿⣿⣿⣿⣿⡿⠁⠄⠄⠄⠄
⠏⠄⠄⠄⠄⠄⠐⣠⠞⠋⣽⠾⠛⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠄

⠄⠄⣠⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣿⠏⢹⣿⠏⠁⠿⠋⠸⠟⠋⠿⠿⠿⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⡏⠸⠟⠄⠄⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠙⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⠟⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠙⠻⣿⣿⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⡟⠁⠄⠄⠄⠄⠄⠄⠄⢀⣤⣴⣶⣿⣿⣿⣿⣿⣿⣿⣷⣶⣦⣤⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠻⣿⣿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄⠄⢀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⡀⠄⠄⠄⠄⠄⠄⠄⠄⠘⢿⣿⣿⠄
⠄⠄⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄⠄⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡀⠄⠄⠄⠄⠄⠄⠄⠄⠻⣿⠄
⠄⠄⣿⣿⣿⣿⣿⠃⠄⠄⠄⠄⠄⠄⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠄⠄⠄⠄⠄⠄⠄⠄⠙⠄
⠄⠄⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄⠄⠄⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠙⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠄⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡀⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⠃⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣷⣄⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣶⣤⡀⠄⠄⠄⠄⢰⣶⡄⠄⠄⠄⠄⠄⠄⠄⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠄⠄⠄⢸⣿⣿⣆⠄⠄⠄⠄⠄⠄⠄⠄⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡅⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⠄⠄⠸⣿⣿⣿⣷⠄⠄⠄⠄⠄⢀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⠄⠄⠄⢻⣿⣿⣷⣶⣿⣶⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠃⠄⠄⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡀⠄⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠆⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣶⣶⣶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⠅⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠙⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠛⠋⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠉⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠏⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠙⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡤⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠛⠋⠙⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠋⠉⠙⠛⠋⠉⠉⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⣀⣀⣀⣀⣀⠄⠄⠄⠄⠄⢀⣀⣀⣀⣀⡀⠄⠄⠄⢀⣀⣀⣀⣀⣀⠄⠄⢀⣀⣀⣀⡀⢀⣀⣀⣀⣀⠄⠄⠄⠄⠄⠄⢀⣀⣀⣀⡀⠄
⠄⠄⢹⣿⡏⠄⠄⠄⠄⠄⠄⠄⠈⣿⣿⠁⠄⠄⠄⠄⠄⠈⢿⣿⡅⠄⠄⠄⠄⢸⡟⠁⠄⠄⠄⣿⢻⣿⡄⠄⠄⠄⠄⠄⡼⢿⣿⡇⠄⠄
⠄⠄⢸⣿⡇⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⠄⠄⠄⠄⠄⠄⠄⠘⣿⣷⠄⠄⠄⢠⡟⠄⠄⠄⠄⠄⣿⠈⢿⣿⡄⠄⠄⠄⣸⠁⢸⣿⡇⠄⠄
⠄⠄⢸⣿⡇⠄⠄⠄⠄⠄⠄⠄⠄⣿⣿⠄⠄⠄⠄⠄⠄⠄⠄⠹⣿⣆⠄⠄⡾⠁⠄⠄⠄⠄⠄⣿⠄⠈⣿⣷⡀⠄⣰⠃⠄⢸⣿⡇⠄⠄
⠄⠄⢸⣿⡇⠄⠄⠄⠄⠄⢀⠄⠄⣿⣿⠄⠄⠄⠄⠄⠄⡀⠄⠄⢻⣿⡄⣼⠃⠄⠄⠄⠄⠄⠄⣿⠄⠄⠘⣿⣧⣰⠇⠄⠄⢸⣿⡇⠄⠄
⠄⠄⢸⣿⡇⠄⠄⠄⠄⣠⡟⠄⠄⣿⣿⠄⠄⠄⠄⢀⣼⠁⠄⠄⠈⣿⣿⠃⠄⠄⠄⠄⠄⠄⠄⣿⠄⠄⠄⠹⣿⠏⠄⠄⠄⣸⣿⡇⠄⠄
⠄⠒⠛⠛⠓⠒⠒⠒⠛⠛⠁⠐⠚⠛⠛⠒⠒⠒⠚⠛⠋⠄⠄⠄⠄⠘⠏⠄⠄⠄⠄⠄⠄⠒⠚⠛⠓⠂⠄⠄⠉⠄⠄⠐⠒⠛⠛⠓⠂⠄