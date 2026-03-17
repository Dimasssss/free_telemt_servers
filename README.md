# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 06:55:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 43784.1 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270480
telemt_connections_bad_total 3388
telemt_handshake_timeouts_total 8505
telemt_upstream_connect_attempt_total 9086
telemt_upstream_connect_success_total 9038
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6888
telemt_me_reconnect_success_total 6863
telemt_me_reader_eof_total 7307
telemt_me_idle_close_by_peer_total 7307
telemt_me_route_drop_no_conn_total 82401
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242463
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1768
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 886
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 6934
telemt_me_writer_restored_same_endpoint_total 6842
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 242247
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 3156529112 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 106291097968 (98.99 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 44035.2 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151204
telemt_connections_bad_total 2210
telemt_handshake_timeouts_total 11568
telemt_upstream_connect_attempt_total 12113
telemt_upstream_connect_success_total 11963
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 12113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 10974
telemt_me_reconnect_success_total 9795
telemt_me_reader_eof_total 10342
telemt_me_idle_close_by_peer_total 10342
telemt_me_route_drop_no_conn_total 55632
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131450
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9920
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9779
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 131476
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 1612853692 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 56661627664 (52.77 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 43811.4 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90700
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 3098
telemt_upstream_connect_attempt_total 11657
telemt_upstream_connect_success_total 11597
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9453
telemt_me_reconnect_success_total 9400
telemt_me_reader_eof_total 10062
telemt_me_idle_close_by_peer_total 10062
telemt_me_route_drop_no_conn_total 30394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78141
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9513
telemt_me_writer_restored_same_endpoint_total 9389
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 78100
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 6225471464 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 25074882912 (23.35 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 43870.7 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166276
telemt_connections_bad_total 5813
telemt_handshake_timeouts_total 9228
telemt_upstream_connect_attempt_total 10008
telemt_upstream_connect_success_total 9924
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_reconnect_attempts_total 7749
telemt_me_reconnect_success_total 7687
telemt_me_reader_eof_total 8161
telemt_me_idle_close_by_peer_total 8161
telemt_me_route_drop_no_conn_total 53602
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145882
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 272
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7796
telemt_me_writer_restored_same_endpoint_total 7680
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 145892
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 1580770290 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 69458877833 (64.69 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 43842.5 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122310
telemt_connections_bad_total 36516
telemt_handshake_timeouts_total 2379
telemt_upstream_connect_attempt_total 13332
telemt_upstream_connect_success_total 13158
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 13332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_reconnect_attempts_total 14125
telemt_me_reconnect_success_total 10865
telemt_me_reader_eof_total 11484
telemt_me_idle_close_by_peer_total 11484
telemt_me_route_drop_no_conn_total 31895
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80097
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11106
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 10857
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 80143
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 817201803 (779.34 MB)
telemt_user_octets_to_client{user="hello"} 36900957530 (34.37 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 44003.9 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290760
telemt_connections_bad_total 42097
telemt_handshake_timeouts_total 2317
telemt_upstream_connect_attempt_total 8913
telemt_upstream_connect_success_total 8867
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6724
telemt_me_reconnect_success_total 6693
telemt_me_reader_eof_total 7174
telemt_me_idle_close_by_peer_total 7174
telemt_me_route_drop_no_conn_total 227360
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 306
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 6794
telemt_me_writer_restored_same_endpoint_total 6683
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 235034
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 3416767252 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 157787591696 (146.95 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32010.1 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1362
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15991
telemt_upstream_connect_success_total 15991
telemt_upstream_connect_attempts_per_request{bucket="1"} 15991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 14404
telemt_me_reconnect_success_total 14325
telemt_me_reader_eof_total 15657
telemt_me_idle_close_by_peer_total 15657
telemt_me_route_drop_no_conn_total 145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1154
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 14454
telemt_me_writer_restored_same_endpoint_total 14325
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1154
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 204341856 (194.88 MB)
telemt_user_octets_to_client{user="hello"} 12980132356 (12.09 GB)
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```