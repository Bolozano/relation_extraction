# relation_extraction
!pip install -q transformers 

import torch
from transformers import BertTokenizer, BertModel
import string
from tqdm.notebook import tqdm
import pickle
import gc
import re
import json
import time
import numpy as np
import matplotlib as plt
