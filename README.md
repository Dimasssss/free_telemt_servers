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

# Server Metrics 2026-03-17 07:25:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 45615.1 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295706
telemt_connections_bad_total 3515
telemt_handshake_timeouts_total 9487
telemt_upstream_connect_attempt_total 9413
telemt_upstream_connect_success_total 9362
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7126
telemt_me_reconnect_success_total 7099
telemt_me_reader_eof_total 7558
telemt_me_idle_close_by_peer_total 7558
telemt_me_route_drop_no_conn_total 89970
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265399
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1987
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1398
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7172
telemt_me_writer_restored_same_endpoint_total 7078
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 265173
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 3497912452 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 116330273320 (108.34 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 45866.6 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167211
telemt_connections_bad_total 2347
telemt_handshake_timeouts_total 11825
telemt_upstream_connect_attempt_total 12506
telemt_upstream_connect_success_total 12345
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 12506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 11271
telemt_me_reconnect_success_total 10088
telemt_me_reader_eof_total 10657
telemt_me_idle_close_by_peer_total 10657
telemt_me_route_drop_no_conn_total 60355
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144222
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 381
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10218
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10072
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 144268
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 1781178496 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 60314234656 (56.17 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 45643.0 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99674
telemt_connections_bad_total 2574
telemt_handshake_timeouts_total 4140
telemt_upstream_connect_attempt_total 12002
telemt_upstream_connect_success_total 11939
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 12002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9709
telemt_me_reconnect_success_total 9654
telemt_me_reader_eof_total 10336
telemt_me_idle_close_by_peer_total 10336
telemt_me_route_drop_no_conn_total 32420
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9773
telemt_me_writer_restored_same_endpoint_total 9643
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 84349
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 6327504604 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 26213016296 (24.41 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 45702.1 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193131
telemt_connections_bad_total 5830
telemt_handshake_timeouts_total 9902
telemt_upstream_connect_attempt_total 10426
telemt_upstream_connect_success_total 10338
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 10426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8076
telemt_me_reconnect_success_total 8010
telemt_me_reader_eof_total 8505
telemt_me_idle_close_by_peer_total 8505
telemt_me_route_drop_no_conn_total 58435
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163422
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8125
telemt_me_writer_restored_same_endpoint_total 8002
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 163429
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 1727782486 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 75134309969 (69.97 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 45673.9 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130036
telemt_connections_bad_total 38312
telemt_handshake_timeouts_total 2438
telemt_upstream_connect_attempt_total 13882
telemt_upstream_connect_success_total 13703
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 14579
telemt_me_reconnect_success_total 11317
telemt_me_reader_eof_total 11961
telemt_me_idle_close_by_peer_total 11961
telemt_me_route_drop_no_conn_total 33796
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11562
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 85756
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 866603255 (826.46 MB)
telemt_user_octets_to_client{user="hello"} 40296627050 (37.53 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 45835.2 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307889
telemt_connections_bad_total 42165
telemt_handshake_timeouts_total 2612
telemt_upstream_connect_attempt_total 9438
telemt_upstream_connect_success_total 9390
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 7157
telemt_me_reconnect_success_total 7122
telemt_me_reader_eof_total 7606
telemt_me_idle_close_by_peer_total 7606
telemt_me_route_drop_no_conn_total 234932
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329298
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7227
telemt_me_writer_restored_same_endpoint_total 7108
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 251230
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 3617597868 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 161457965204 (150.37 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33841.4 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 16927
telemt_upstream_connect_success_total 16926
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15254
telemt_me_reconnect_success_total 15166
telemt_me_reader_eof_total 16593
telemt_me_idle_close_by_peer_total 16593
telemt_me_route_drop_no_conn_total 205
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1357
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15301
telemt_me_writer_restored_same_endpoint_total 15166
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 1357
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 214836508 (204.88 MB)
telemt_user_octets_to_client{user="hello"} 14893753068 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```