# Pikachu
#---APP FOR FAREWALL-----
import streamlit as st
from PIL import Image
import requests

st.set_page_config(page_title="What's up?", page_icon= "ps:fuck", layout = "wide")

#---LOAD ASSESTS----

img_pikachu_meme = Image.open("pikachu.png.webp")

#----Header SECTION-----

with st.container():
    right_column, left_column =st.columns(2)
    with left_column:
     st.header("What, up bitch?????")
     st.subheader("I hope u have a safe flight to Ch***.... Taiwan")

    #---INSERT IMAGE---
    with right_column:
     st.image(img_pikachu_meme)
     st.header("This is probably my last pika pika, so enjoy it")
     st.subheader("PIKA...PIKA...CHUUUUUUUUUUUUUUUUU")
