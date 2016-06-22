https://linkedin-oath.herokuapp.com/

to generate a random key:

node -e "require('crypto').randomBytes(48, (ex, buf) => {
    console.log(buf.toString('hex'))
});")
