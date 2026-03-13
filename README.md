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

# Server Metrics 2026-03-13 12:11:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 103118.9 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418990
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 8354
telemt_upstream_connect_attempt_total 26142
telemt_upstream_connect_success_total 26018
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 26141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2370
telemt_me_reconnect_attempts_total 24369
telemt_me_reconnect_success_total 20842
telemt_me_reader_eof_total 22240
telemt_me_idle_close_by_peer_total 22239
telemt_me_route_drop_no_conn_total 133111
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1223
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21170
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20826
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 363063
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 6441926084 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 155948876880 (145.24 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 103011.9 (28h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193308
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 1463
telemt_upstream_connect_attempt_total 55620
telemt_upstream_connect_success_total 54925
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 55620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 547
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 1347
telemt_me_reconnect_attempts_total 95580
telemt_me_reconnect_success_total 25941
telemt_me_reader_eof_total 28877
telemt_me_idle_close_by_peer_total 28877
telemt_me_route_drop_no_conn_total 79012
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158653
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28341
telemt_me_refill_failed_total 2172
telemt_me_writer_restored_same_endpoint_total 25924
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2400
telemt_user_connections_total{user="hello"} 182258
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 1857967889 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 59152758236 (55.09 GB)
telemt_user_msgs_from_client{user="hello"} 344068
telemt_user_msgs_to_client{user="hello"} 2428015
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 102976.1 (28h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234945
telemt_connections_bad_total 2063
telemt_handshake_timeouts_total 7094
telemt_upstream_connect_attempt_total 28007
telemt_upstream_connect_success_total 28003
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2159
telemt_me_reconnect_attempts_total 24003
telemt_me_reconnect_success_total 22792
telemt_me_reader_eof_total 24417
telemt_me_idle_close_by_peer_total 24417
telemt_me_route_drop_no_conn_total 87145
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217239
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 23044
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22772
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 217153
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 9334517640 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 96751550676 (90.11 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 102951.5 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327557
telemt_connections_bad_total 13765
telemt_handshake_timeouts_total 2378
telemt_upstream_connect_attempt_total 39887
telemt_upstream_connect_success_total 29812
telemt_upstream_connect_fail_total 10075
telemt_upstream_connect_attempts_per_request{bucket="1"} 39887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10075
telemt_me_keepalive_timeout_total 4033
telemt_me_reconnect_attempts_total 93148
telemt_me_reconnect_success_total 21596
telemt_me_reader_eof_total 24478
telemt_me_idle_close_by_peer_total 24471
telemt_me_route_drop_no_conn_total 118552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282533
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24100
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21586
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2504
telemt_user_connections_total{user="hello"} 285447
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 5925381598 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 107696642713 (100.30 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53122.9 (14h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77017
telemt_connections_bad_total 10514
telemt_handshake_timeouts_total 804
telemt_upstream_connect_attempt_total 23115
telemt_upstream_connect_success_total 22936
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 23115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 25289
telemt_me_reconnect_success_total 15373
telemt_me_reader_eof_total 16496
telemt_me_idle_close_by_peer_total 16496
telemt_me_route_drop_no_conn_total 22772
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58309
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 15815
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15355
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 63220
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 551871809 (526.31 MB)
telemt_user_octets_to_client{user="hello"} 17549353187 (16.34 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 102907.8 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586358
telemt_connections_bad_total 17431
telemt_handshake_timeouts_total 13540
telemt_upstream_connect_attempt_total 21875
telemt_upstream_connect_success_total 21761
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 21875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2450
telemt_me_reconnect_attempts_total 21245
telemt_me_reconnect_success_total 16625
telemt_me_reader_eof_total 17846
telemt_me_idle_close_by_peer_total 17843
telemt_me_route_drop_no_conn_total 289836
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562279
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 16987
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16618
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 535338
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 9552620968 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 287028236936 (267.32 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 62
```