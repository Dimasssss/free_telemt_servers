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

# Server Metrics 2026-03-16 11:44:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 134974.7 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735070
telemt_connections_bad_total 53955
telemt_handshake_timeouts_total 23451
telemt_upstream_connect_attempt_total 31147
telemt_upstream_connect_success_total 30999
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 31147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 38541
telemt_me_reconnect_success_total 24313
telemt_me_reader_eof_total 26248
telemt_me_idle_close_by_peer_total 26248
telemt_me_route_drop_no_conn_total 602454
telemt_me_route_drop_channel_closed_total 92
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677672
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3151
telemt_desync_full_logged_total 1204
telemt_desync_suppressed_total 1947
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 1261
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 123
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25020
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24278
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 707
telemt_user_connections_total{user="hello"} 614184
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 11780193824 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 359342854920 (334.66 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 134981.7 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299792
telemt_connections_bad_total 3814
telemt_handshake_timeouts_total 19232
telemt_upstream_connect_attempt_total 36244
telemt_upstream_connect_success_total 36137
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 827
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 40200
telemt_me_reconnect_success_total 28823
telemt_me_reader_eof_total 30898
telemt_me_idle_close_by_peer_total 30897
telemt_me_route_drop_no_conn_total 143834
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265393
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29585
telemt_me_refill_failed_total 346
telemt_me_writer_restored_same_endpoint_total 28807
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 265094
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 5453525925 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 133725202316 (124.54 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 134974.5 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293308
telemt_connections_bad_total 5935
telemt_handshake_timeouts_total 8210
telemt_upstream_connect_attempt_total 37447
telemt_upstream_connect_success_total 37438
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38108
telemt_me_reconnect_success_total 30674
telemt_me_reader_eof_total 32940
telemt_me_idle_close_by_peer_total 32939
telemt_me_route_drop_no_conn_total 100430
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239538
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 31218
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30666
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 239138
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 18833085097 (17.54 GB)
telemt_user_octets_to_client{user="hello"} 128219200152 (119.41 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 134974.1 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440274
telemt_connections_bad_total 1459
telemt_handshake_timeouts_total 4071
telemt_upstream_connect_attempt_total 31162
telemt_upstream_connect_success_total 31118
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 31162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29411
telemt_me_reconnect_success_total 24409
telemt_me_reader_eof_total 26147
telemt_me_idle_close_by_peer_total 26146
telemt_me_route_drop_no_conn_total 149798
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406989
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 24894
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24398
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 406847
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 6432546026 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 156572744828 (145.82 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 110045.5 (30h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273834
telemt_connections_bad_total 47808
telemt_handshake_timeouts_total 4390
telemt_upstream_connect_attempt_total 31444
telemt_upstream_connect_success_total 31273
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 31444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121213
telemt_me_reconnect_success_total 25609
telemt_me_reader_eof_total 27203
telemt_me_idle_close_by_peer_total 27203
telemt_me_route_drop_no_conn_total 82900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213229
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 25866
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25505
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 212848
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2794597765 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 96487823051 (89.86 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 134973.6 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954811
telemt_connections_bad_total 73911
telemt_handshake_timeouts_total 11306
telemt_upstream_connect_attempt_total 28534
telemt_upstream_connect_success_total 28383
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 28534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24280
telemt_me_reconnect_success_total 21661
telemt_me_reader_eof_total 23109
telemt_me_idle_close_by_peer_total 23108
telemt_me_route_drop_no_conn_total 700440
telemt_me_route_drop_channel_closed_total 130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936811
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 580
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 22005
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21634
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 795413
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 16469699072 (15.34 GB)
telemt_user_octets_to_client{user="hello"} 457196340216 (425.80 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 110
```