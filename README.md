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

# Server Metrics 2026-03-16 12:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 138970.1 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779500
telemt_connections_bad_total 54223
telemt_handshake_timeouts_total 25003
telemt_upstream_connect_attempt_total 32093
telemt_upstream_connect_success_total 31937
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 32093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39254
telemt_me_reconnect_success_total 25019
telemt_me_reader_eof_total 26984
telemt_me_idle_close_by_peer_total 26984
telemt_me_route_drop_no_conn_total 614453
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715100
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3415
telemt_desync_full_logged_total 1282
telemt_desync_suppressed_total 2133
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 1427
telemt_desync_frames_bucket_total{bucket="gt_10"} 1269
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25737
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24984
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 651575
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 13610258428 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 375007487684 (349.25 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 138977.7 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326164
telemt_connections_bad_total 4675
telemt_handshake_timeouts_total 21037
telemt_upstream_connect_attempt_total 37138
telemt_upstream_connect_success_total 37031
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43425
telemt_me_reconnect_success_total 29478
telemt_me_reader_eof_total 31653
telemt_me_idle_close_by_peer_total 31652
telemt_me_route_drop_no_conn_total 154004
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288492
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30336
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29462
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 858
telemt_user_connections_total{user="hello"} 288173
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 5806107661 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 141164094484 (131.47 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 138970.2 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312134
telemt_connections_bad_total 6190
telemt_handshake_timeouts_total 8989
telemt_upstream_connect_attempt_total 38354
telemt_upstream_connect_success_total 38346
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38795
telemt_me_reconnect_success_total 31348
telemt_me_reader_eof_total 33653
telemt_me_idle_close_by_peer_total 33652
telemt_me_route_drop_no_conn_total 106112
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 31902
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31340
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 255138
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 18988723109 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 132121831896 (123.05 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 138969.9 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475598
telemt_connections_bad_total 3121
telemt_handshake_timeouts_total 6028
telemt_upstream_connect_attempt_total 32232
telemt_upstream_connect_success_total 32185
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 32232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 30254
telemt_me_reconnect_success_total 25244
telemt_me_reader_eof_total 27012
telemt_me_idle_close_by_peer_total 27011
telemt_me_route_drop_no_conn_total 159824
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437356
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1567
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25738
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 25233
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 437180
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 6689773890 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 165092284192 (153.75 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 114041.1 (31h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296714
telemt_connections_bad_total 54887
telemt_handshake_timeouts_total 5228
telemt_upstream_connect_attempt_total 32415
telemt_upstream_connect_success_total 32236
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 32415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 122006
telemt_me_reconnect_success_total 26389
telemt_me_reader_eof_total 28026
telemt_me_idle_close_by_peer_total 28026
telemt_me_route_drop_no_conn_total 88212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227561
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26659
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26285
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 227141
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2942079837 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 104786075935 (97.59 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 138969.3 (38h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009753
telemt_connections_bad_total 77995
telemt_handshake_timeouts_total 12859
telemt_upstream_connect_attempt_total 29461
telemt_upstream_connect_success_total 29307
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 29461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 26000
telemt_me_reconnect_success_total 22348
telemt_me_reader_eof_total 23869
telemt_me_idle_close_by_peer_total 23868
telemt_me_route_drop_no_conn_total 720054
telemt_me_route_drop_channel_closed_total 138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980039
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 703
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22736
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22321
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 838619
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 17873044760 (16.65 GB)
telemt_user_octets_to_client{user="hello"} 480680761980 (447.67 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 109
```