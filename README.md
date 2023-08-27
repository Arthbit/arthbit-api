# Arthbit API Endpoint

- SUMMARY ENDPOINT
api.arthbit.com/v1/summary

Sample Response
{
        "trading_pairs": "INR_AMP",
        "last_price": 448.0,
        "lowest_ask": 447.0,
        "highest_bid": 362.0,
        "quote_volume": 1212.1389,
        "price_change_percent_24h": 23.76,
        "highest_price_24h": 449.0,
        "lowest_price_24h": 362.0
    },
    {
        "trading_pairs": "USDT_CSC",
        "last_price": 52.2,
        "lowest_ask": 52.5,
        "highest_bid": 5.01,
        "quote_volume": 0.777,
        "price_change_percent_24h": 0.0,
        "highest_price_24h": 52.2,
        "lowest_price_24h": 52.2
    },


- Ticker 
api.arthbit.com/v1/ticker

Sample Response
{
        "INR_AMP": {
            "quote_id": 0,
            "last_price": 448.0,
            "quote_volume": 1212.1389,
            "is_frozen": 1
        }
    },
    {
        "USDT_CSC": {
            "quote_id": 0,
            "last_price": 52.2,
            "quote_volume": 0.777,
            "is_frozen": 1
        }

- Assets
api.arthbit.com/v1/assets

Sample Response
{
        "AMP": {
            "name": "Ample Coin",
            "unified_cryptoasset_id": 0,
            "can_withdrawal": true,
            "can_deposit": true,
            "minWithdrawAmount": 0.0,
            "maxWithdrawAmount": 0.0,
            "currency_fullname": "Ample Coin",
            "maker_fee": 0.4012,
            "taker_fee": 0.4012
        }
    },
    {
        "CSC": {
            "name": "Crassulla",
            "unified_cryptoasset_id": 0,
            "can_withdrawal": true,
            "can_deposit": true,
            "minWithdrawAmount": 0.0,
            "maxWithdrawAmount": 0.0,
            "currency_fullname": "Crassulla",
            "maker_fee": 0.4012,
            "taker_fee": 0.4012
        }
    },

- Trades
api.arthbit.com/v1/trades/?market_pair=inr_btc

Sample Response 
{
        "trade_id": 5419757,
        "price": 2356977.35,
        "quote_volume": 0.000878,
        "timestamp": 1693145232,
        "type": "SELL"
    },
    {
        "trade_id": 5419748,
        "price": 2361856.14,
        "quote_volume": 0.00074,
        "timestamp": 1693145232,
        "type": "BUY"
    },

- Order Book 
api.arthbit.com/v1/orderbook/?market_pair=INR_BTC

"timestamp": 1693145339,
    "bids": [
        [
            2316720.88,
            0.001097
        ],
        [
            2316720.88,
            0.000485
        ],
        [
            2316720.86,
            0.001658
        ],
        [
            2316720.85,
            0.001576
        ],
        [
            2316720.81,
            0.000968
        ],
        [
            2316720.78,
            0.000699
        ],
        [
            2316720.74,
            0.000684
        ],
        [
            2316720.68,
            0.001636
        ],
        [
            2316720.58,
            0.001996
        ],
        [
            2316720.57,
            0.000663
        ]
    ],
    "asks": [
        [
            2357720.94,
            0.001314
        ],
        [
            2357720.94,
            0.000104
        ],
        [
            2357721.05,
            0.001607
        ],
        [
            2357721.5,
            0.001357
        ],
        [
            2357721.6,
            0.001169
        ],
        [
            2357723.83,
            0.001944
        ],
        [
            2357725.78,
            0.000254
        ],
        [
            2357726.37,
            0.000762
        ],
        [
            2357730.3,
            0.009216
        ],
        [
            2357746.85,
            0.008934
        ]
    ]






