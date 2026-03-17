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

# Server Metrics 2026-03-17 09:43:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 53865.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426447
telemt_connections_bad_total 3675
telemt_handshake_timeouts_total 12304
telemt_upstream_connect_attempt_total 13711
telemt_upstream_connect_success_total 13279
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 13711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9839
telemt_me_reconnect_success_total 8316
telemt_me_reader_eof_total 8835
telemt_me_idle_close_by_peer_total 8834
telemt_me_route_drop_no_conn_total 134422
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384512
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3077
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 2241
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 950
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8486
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8294
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 386487
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 5553203559 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 153658618807 (143.11 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 54116.8 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232225
telemt_connections_bad_total 2553
telemt_handshake_timeouts_total 13512
telemt_upstream_connect_attempt_total 14140
telemt_upstream_connect_success_total 13945
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 14140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 18618
telemt_me_reconnect_success_total 11254
telemt_me_reader_eof_total 12046
telemt_me_idle_close_by_peer_total 12046
telemt_me_route_drop_no_conn_total 84644
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204458
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 546
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11597
telemt_me_refill_failed_total 229
telemt_me_writer_restored_same_endpoint_total 11238
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 204463
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 2486249436 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 79009630036 (73.58 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 53893.5 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142641
telemt_connections_bad_total 7578
telemt_handshake_timeouts_total 9896
telemt_upstream_connect_attempt_total 14344
telemt_upstream_connect_success_total 14269
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12535
telemt_me_reconnect_success_total 11568
telemt_me_reader_eof_total 12362
telemt_me_idle_close_by_peer_total 12362
telemt_me_route_drop_no_conn_total 43298
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115799
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 360
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11748
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11557
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 115721
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 7572147324 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 35965003560 (33.50 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 53952.2 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313853
telemt_connections_bad_total 6191
telemt_handshake_timeouts_total 10937
telemt_upstream_connect_attempt_total 12254
telemt_upstream_connect_success_total 12141
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 12254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10487
telemt_me_reconnect_success_total 9401
telemt_me_reader_eof_total 9993
telemt_me_idle_close_by_peer_total 9993
telemt_me_route_drop_no_conn_total 86642
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252615
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9580
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9393
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 252573
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 2693387874 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 101563888829 (94.59 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 53924.2 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175351
telemt_connections_bad_total 47892
telemt_handshake_timeouts_total 2778
telemt_upstream_connect_attempt_total 16392
telemt_upstream_connect_success_total 16179
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 16392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_reconnect_attempts_total 20500
telemt_me_reconnect_success_total 13383
telemt_me_reader_eof_total 14194
telemt_me_idle_close_by_peer_total 14194
telemt_me_route_drop_no_conn_total 45712
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119317
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 381
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 13772
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13375
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 119344
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 1838292235 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 54346797630 (50.61 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 54085.5 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412505
telemt_connections_bad_total 48135
telemt_handshake_timeouts_total 4252
telemt_upstream_connect_attempt_total 11054
telemt_upstream_connect_success_total 10994
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12169
telemt_me_reconnect_success_total 8289
telemt_me_reader_eof_total 8949
telemt_me_idle_close_by_peer_total 8949
telemt_me_route_drop_no_conn_total 273603
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8539
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8275
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 337535
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 4841743028 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 188328822800 (175.39 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 1852.2 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1862
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 546
telemt_upstream_connect_success_total 526
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 311
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 287
telemt_me_idle_close_by_peer_total 287
telemt_me_route_drop_no_conn_total 620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1627
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 299
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1733
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 21454705 (20.46 MB)
telemt_user_octets_to_client{user="hello"} 7003785886 (6.52 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 5
```