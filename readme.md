# Steps Init Server
1. Console "npm install";
2. Rename .env.example to .env and set your own values (XAMPP with PhP admin was used for emulation for the database) or use default:

                            PORT=3000
                            DB_DATABASE='student_db'
                            DB_HOST='localhost'
                            DB_USER='root'
                            DB_PASSWORD=''
                            DB_PORT=3306

                            SALT= 1-10
                            JWT_SECRET= XOXOXOOXOXOX (as an example);

4. Import  SQL from /src/data/student_db.sql;

5. Run the server with command: "npm start", server restarts everytime a change is made;
