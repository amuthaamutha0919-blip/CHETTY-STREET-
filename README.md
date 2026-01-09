import streamlit as st
import pandas as pd
from datetime import datetime, time

# --- ரகசிய பாஸ்வேர்டு ---
ADMIN_PASSWORD = "admintest@123"

# பக்க அமைப்பு
st.set_page_config(page_title="எங்கள் தெரு நிர்வாகம்", layout="wide")
