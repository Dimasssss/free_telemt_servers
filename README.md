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

# Server Metrics 2026-03-19 07:09:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 33681.1 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571006
telemt_connections_bad_total 59856
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_handshake_timeouts_total 23292
telemt_upstream_connect_attempt_total 6534
telemt_upstream_connect_success_total 6413
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 6534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 5866
telemt_me_reconnect_success_total 4716
telemt_me_reader_eof_total 5002
telemt_me_idle_close_by_peer_total 5001
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 159353
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427050
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2783
telemt_desync_full_logged_total 789
telemt_desync_suppressed_total 1994
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4804
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4699
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 424186
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 5794199968 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 142973600336 (133.15 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 33685.4 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1296795
telemt_connections_bad_total 71379
telemt_connections_current 3915
telemt_connections_me_current 3915
telemt_handshake_timeouts_total 31438
telemt_upstream_connect_attempt_total 6344
telemt_upstream_connect_success_total 6222
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 6344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5667
telemt_me_reconnect_success_total 4513
telemt_me_reader_eof_total 4789
telemt_me_idle_close_by_peer_total 4789
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 558927
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073095
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4692
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 3099
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1753
telemt_desync_frames_bucket_total{bucket="gt_10"} 2076
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4634
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4492
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 1073022
telemt_user_connections_current{user="hello"} 3915
telemt_user_octets_from_client{user="hello"} 20849259648 (19.42 GB)
telemt_user_octets_to_client{user="hello"} 442967985944 (412.55 GB)
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 611
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 33681.8 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107054
telemt_connections_bad_total 159143
telemt_connections_current 3129
telemt_connections_me_current 3129
telemt_handshake_timeouts_total 31041
telemt_upstream_connect_attempt_total 6093
telemt_upstream_connect_success_total 6093
telemt_upstream_connect_attempts_per_request{bucket="1"} 6093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4410
telemt_me_reconnect_success_total 4388
telemt_me_reader_eof_total 4644
telemt_me_idle_close_by_peer_total 4644
telemt_me_route_drop_no_conn_total 488029
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831030
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3848
telemt_desync_full_logged_total 1215
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 1390
telemt_desync_frames_bucket_total{bucket="gt_10"} 1706
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4468
telemt_me_writer_restored_same_endpoint_total 4372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 830677
telemt_user_connections_current{user="hello"} 3129
telemt_user_octets_from_client{user="hello"} 14803954364 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 427842040200 (398.46 GB)
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 33735.4 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134893
telemt_connections_bad_total 89338
telemt_connections_current 2865
telemt_connections_me_current 2865
telemt_handshake_timeouts_total 29061
telemt_upstream_connect_attempt_total 5920
telemt_upstream_connect_success_total 5920
telemt_upstream_connect_attempts_per_request{bucket="1"} 5920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5263
telemt_me_reconnect_success_total 4202
telemt_me_reader_eof_total 4468
telemt_me_idle_close_by_peer_total 4467
telemt_me_route_drop_no_conn_total 409541
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790504
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3015
telemt_desync_full_logged_total 1061
telemt_desync_suppressed_total 1954
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 1264
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4294
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4178
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 789360
telemt_user_connections_current{user="hello"} 2865
telemt_user_octets_from_client{user="hello"} 11653812612 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 285201840640 (265.61 GB)
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 33678.7 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1405571
telemt_connections_bad_total 399503
telemt_connections_current 3187
telemt_connections_me_current 3187
telemt_handshake_timeouts_total 31321
telemt_upstream_connect_attempt_total 5953
telemt_upstream_connect_success_total 5916
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4245
telemt_me_reconnect_success_total 4213
telemt_me_reader_eof_total 4461
telemt_me_idle_close_by_peer_total 4461
telemt_me_route_drop_no_conn_total 348973
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837452
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4176
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 2870
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1361
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4266
telemt_me_writer_restored_same_endpoint_total 4189
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 837180
telemt_user_connections_current{user="hello"} 3187
telemt_user_octets_from_client{user="hello"} 18650503872 (17.37 GB)
telemt_user_octets_to_client{user="hello"} 423235727068 (394.17 GB)
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 33690.3 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234658
telemt_connections_bad_total 12639
telemt_connections_current 811
telemt_connections_me_current 811
telemt_handshake_timeouts_total 2096
telemt_upstream_connect_attempt_total 8928
telemt_upstream_connect_success_total 8698
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 8928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12366
telemt_me_reconnect_success_total 6993
telemt_me_reader_eof_total 7424
telemt_me_idle_close_by_peer_total 7424
telemt_me_route_drop_no_conn_total 111464
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207645
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7200
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 6963
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 207627
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 3215463040 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 106179557296 (98.89 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 33681.2 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880801
telemt_connections_bad_total 89216
telemt_connections_current 3008
telemt_connections_me_current 3008
telemt_handshake_timeouts_total 37580
telemt_upstream_connect_attempt_total 6882
telemt_upstream_connect_success_total 6882
telemt_upstream_connect_attempts_per_request{bucket="1"} 6882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6512
telemt_me_reconnect_success_total 5181
telemt_me_reader_eof_total 5493
telemt_me_idle_close_by_peer_total 5493
telemt_me_route_drop_no_conn_total 358775
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720728
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4050
telemt_desync_full_logged_total 1398
telemt_desync_suppressed_total 2652
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 1537
telemt_desync_frames_bucket_total{bucket="gt_10"} 1702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5278
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5166
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 720493
telemt_user_connections_current{user="hello"} 3008
telemt_user_octets_from_client{user="hello"} 10597748000 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 403230392692 (375.54 GB)
telemt_user_unique_ips_current{user="hello"} 946
telemt_user_unique_ips_recent_window{user="hello"} 388
```