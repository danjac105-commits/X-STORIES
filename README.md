<!DOCTYPE html>
<html>
<head>
<title>TechMagic Stories</title>

<style>

body{
margin:0;
height:100vh;
overflow:hidden;
background:#030712;
font-family:Arial;
}

.book{
position:absolute;
top:50%;
left:50%;
transform:translate(-50%,-50%);
width:350px;
height:220px;
background:linear-gradient(45deg,#00ffff,#0066ff);
border-radius:20px;
box-shadow:0 0 60px cyan;
animation:float 3s infinite ease-in-out;
}

@keyframes float{
50%{
transform:translate(-50%,-55%);
}
}

.magic{
position:absolute;
color:white;
font-size:30px;
animation:rise 6s linear infinite;
}

@keyframes rise{
from{
transform:translateY(0);
opacity:1;
}
to{
transform:translateY(-500px);
opacity:0;
}
}

.menu{
position:absolute;
top:30px;
right:30px;
}

button{
padding:12px 25px;
margin:5px;
border:none;
border-radius:10px;
background:#00ffff;
cursor:pointer;
font-weight:bold;
}

</style>

</head>
<body>

<div class="book"></div>

<div class="magic" style="left:48%;top:40%;">
READ
</div>

<div class="magic" style="left:52%;top:45%;">
MORE
</div>

<div class="magic" style="left:45%;top:42%;">
AND LEARN
</div>

<div class="menu">
<button onclick="location.href='signup.html'">
Sign Up
</button>

<button onclick="location.href='membership.html'">
Membership
</button>

<button onclick="location.href='write.html'">
Write
</button>

<button onclick="location.href='stories.html'">
Our Stories
</button>
</div>

</body>
</html>
<div const mongoose = require("mongoose");
  
<div const UserSchema = new mongoose.Schema({
name:String,
email:{
type:String,
unique:true
},
password:String
});
  </div>

<div class="book module.exports = mongoose.model(User,UserSchema);"
  </div>
<div class="book></div>const mongoose = require(mongoose");
  </div>

<div const StorySchema = new mongoose.Schema({
title:String,
content:String,
author:String,
published:{
type:Boolean,
default:false
},
createdAt:{
type:Date,
default:Date.now
}
});
</div>
<div module.exports =
mongoose.model("Story",StorySchema);<h1>Write Story</h1>
</div>
<input
id="title"
placeholder="Story Title"
/>

<div <textarea
id="content"
placeholder="Write your story..."
></textarea>
</div>
<button id="save">
Save Draft
</button>

<button id="publish">
Publish Story
</button>
<div router.post("/save-draft", async(req,res)=>{
  </div>
<div const story = new Story({
title:req.body.title,
content:req.body.content,
author:req.user.id,
published:false
});
  </div>

<div await story.save();
res.json({
message:Draft Saved
});
});router.post("/publish", async(req,res)=>{
const story = await Story.findById(
req.body.storyId
);
</div>

<div story.published = true;
await story.save();
res.json({
message:Story Published
});
});router.get("/stories",async(req,res)=>{
const stories = await Story.find({
published:true
});
</div>
<div res.json(stories);
});
Post
{
userId,
message,
likes,
comments,
date
}
npm install express mongoose bcryptjs jsonwebtoken cors dotenv
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=TechMagicStoriesSecret
# X-STORIES
</div>
