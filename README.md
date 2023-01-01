```python

'''
Below you can see the technologies I
work with most of the time, so you
can have some ideas of what you
can expect of me :)
'''

# machine learning
import numpy as np
import pandas an pd
import matplotlib.pyplot as plt
import sklearn
import catboost
import optuna  # hyperparameter tuning

# deep learning
import torch
import torch.nn as nn
import torch.optim as optim
from torch.utils import Dataset, DataLoader

# image processing
import cv as cv2
from torchvision import transforms

# backend
from fastapi import FastAPI, Depends, HTTPException
from pydantic import BaseModel

# authentication
from fastapi.security import OAuth2PasswordRequestForm
from uuid import uuid4
from jose import jwt, JWTError
from passlib.context import CryptContext

# databses
import motor.motor_asyncio  # for MongoDB
from sqlalchemy.ext.asyncio import AsyncSession, create_async_engine  # mostly PostgreSQL

# task scheduling
from celery import Celery

# message brokers
import pika
import redis

# containerization
import docker
```
