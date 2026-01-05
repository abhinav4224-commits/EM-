import pickle
import os

with open(os.path.join(os.path.dirname(__file__), "model.pkl"), "rb") as f:
    model = pickle.load(f)

with open(os.path.join(os.path.dirname(__file__), "scaler.pkl"), "rb") as f:
    scaler = pickle.load(f)
