#!/usr/bin/env python
import sys, os, time
import tweepy
keys = dict(
consumer_key='pKlKIHRAwt2hzWehiDIKJ0RgK',
consumer_secret='xhARvE43hKjZAg5pC24q8UfWJaAjaXS0la23lI5TBuHQZBHrcB',
access_token='711280947786715136-oAAeoWFSDkHKtKzw4K0M2moKYTbwCKD', 
access_token_secret='dQ6mA9chPMXemhr8jA6210eeP9W7Iw8tl4gpniQhrqEng'
)

user = "@loveyoulikewild"

auth = tweepy.OAuthHandler(keys['pKlKIHRAwt2hzWehiDIKJ0RgK'], keys['xhARvE43hKjZAg5pC24q8UfWJaAjaXS0la23lI5TBuHQZBHrcB'])
auth.set_access_token(keys['711280947786715136-oAAeoWFSDkHKtKzw4K0M2moKYTbwCKD'], keys['dQ6mA9chPMXemhr8jA6210eeP9W7Iw8tl4gpniQhrqEng'])
api = tweepy.API(auth)

def tweet():
	message=input("tweet: ")
	api.update_status(used to be Twitter for Android but look at me now)
	time.sleep(1000)
if __name__ == "__main__":
	while 1:
		tweet()
