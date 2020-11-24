from flask import Flask,render_template,request,redirect,url_for
import sqlite3

app = Flask(__name__)

@app.route('/')
def example():
    conn = sqlite3.connect('customer.db')
    c = conn.cursor()
    c.execute("SELECT * FROM user")
    result = (c.fetchall())
    conn.commit()
    conn.close()

    return render_template('example.html',result=result)

@app.route('/process',methods=['POST','GET'])
def process():
    username = request.form['username']

    conn = sqlite3.connect('customer.db')
    c = conn.cursor()
    c.execute("INSERT INTO user VALUES('"+username+"')")
    conn.commit()
    conn.close()
    return redirect(url_for('example'))


if __name__== "__main__":
    app.run(port=5002)
