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

# Server Metrics 2026-03-17 10:13:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 55698.9 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456828
telemt_connections_bad_total 3779
telemt_handshake_timeouts_total 12691
telemt_upstream_connect_attempt_total 14051
telemt_upstream_connect_success_total 13618
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 14051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10088
telemt_me_reconnect_success_total 8558
telemt_me_reader_eof_total 9092
telemt_me_idle_close_by_peer_total 9091
telemt_me_route_drop_no_conn_total 144391
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413443
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3318
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1007
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8735
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8536
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 415405
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 6012099687 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 162498169807 (151.34 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 55950.4 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247793
telemt_connections_bad_total 3054
telemt_handshake_timeouts_total 14546
telemt_upstream_connect_attempt_total 14406
telemt_upstream_connect_success_total 14203
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 14406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20123
telemt_me_reconnect_success_total 11412
telemt_me_reader_eof_total 12254
telemt_me_idle_close_by_peer_total 12254
telemt_me_route_drop_no_conn_total 90955
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217979
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11803
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11396
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 217978
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 2661722612 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 82564990008 (76.89 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 55726.7 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151892
telemt_connections_bad_total 7600
telemt_handshake_timeouts_total 11190
telemt_upstream_connect_attempt_total 14865
telemt_upstream_connect_success_total 14787
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 14865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12961
telemt_me_reconnect_success_total 11992
telemt_me_reader_eof_total 12794
telemt_me_idle_close_by_peer_total 12794
telemt_me_route_drop_no_conn_total 45581
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123511
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12181
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11981
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 123424
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 9678046484 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 37905778488 (35.30 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 55785.6 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338236
telemt_connections_bad_total 6200
telemt_handshake_timeouts_total 11470
telemt_upstream_connect_attempt_total 12729
telemt_upstream_connect_success_total 12610
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10871
telemt_me_reconnect_success_total 9778
telemt_me_reader_eof_total 10393
telemt_me_idle_close_by_peer_total 10393
telemt_me_route_drop_no_conn_total 94498
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275220
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 617
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9964
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9770
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 275176
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 3361462818 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 107615977241 (100.23 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 55757.5 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186975
telemt_connections_bad_total 51055
telemt_handshake_timeouts_total 2847
telemt_upstream_connect_attempt_total 17022
telemt_upstream_connect_success_total 16802
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 17022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_reconnect_attempts_total 21035
telemt_me_reconnect_success_total 13911
telemt_me_reader_eof_total 14733
telemt_me_idle_close_by_peer_total 14733
telemt_me_route_drop_no_conn_total 48452
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127446
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 456
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14311
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13903
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 127476
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 1898974339 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 57291499898 (53.36 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 55918.7 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434367
telemt_connections_bad_total 49733
telemt_handshake_timeouts_total 4381
telemt_upstream_connect_attempt_total 11357
telemt_upstream_connect_success_total 11295
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12377
telemt_me_reconnect_success_total 8493
telemt_me_reader_eof_total 9171
telemt_me_idle_close_by_peer_total 9171
telemt_me_route_drop_no_conn_total 283269
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435281
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 8744
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8479
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 357157
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 5152255048 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 193788171140 (180.48 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 3685.6 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3276
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 1482
telemt_upstream_connect_success_total 1458
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 652
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1150
telemt_me_reconnect_success_total 1121
telemt_me_reader_eof_total 1163
telemt_me_idle_close_by_peer_total 1163
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1146
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3023
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1135
telemt_me_writer_restored_same_endpoint_total 1115
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 3129
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 47835973 (45.62 MB)
telemt_user_octets_to_client{user="hello"} 13304164434 (12.39 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 3
```