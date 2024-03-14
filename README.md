def calculate_ema(data, window):
    return data.ewm(span=window, adjust=False).mean()
