#Desafío 31

# 1
"""
CREATE DATABASE call_list; 
"""
# 2
"""
\c call_list
"""
# 3
"""
CREATE TABLE users(
    id integer PRIMARY KEY,
    first_name VARCHAR(50),
    email VARCHAR(50),
);
"""
# 4
"""
INSERT INTO users (id, first_name, email) VALUES (1, 'Carlos', 'carlos@email.com');
"""
# 5
"""
INSERT INTO users (id, first_name, email) VALUES (2, 'Laura', 'laura@email.com');
"""
# 6
"""
CREATE TABLE calls(
    id SERIAL PRIMARY KEY,
    phone VARCHAR,
    user_id INTEGER REFERENCES users(id)
);
"""
# 7
"""

"""
# 8
"""

"""
# 9
"""

"""
# 10
"""

"""
# 11
"""

"""
