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

# Server Metrics 2026-03-16 07:49:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 120880.3 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556720
telemt_connections_bad_total 5762
telemt_handshake_timeouts_total 19539
telemt_upstream_connect_attempt_total 28328
telemt_upstream_connect_success_total 28195
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 28328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25639
telemt_me_reconnect_success_total 22204
telemt_me_reader_eof_total 23761
telemt_me_idle_close_by_peer_total 23761
telemt_me_route_drop_no_conn_total 524767
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553588
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2719
telemt_desync_full_logged_total 1068
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 1081
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22557
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22170
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 492407
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 9470590912 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 318056803200 (296.21 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 120885.9 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222326
telemt_connections_bad_total 3156
telemt_handshake_timeouts_total 15085
telemt_upstream_connect_attempt_total 32540
telemt_upstream_connect_success_total 32465
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32969
telemt_me_reconnect_success_total 26049
telemt_me_reader_eof_total 27890
telemt_me_idle_close_by_peer_total 27889
telemt_me_route_drop_no_conn_total 108938
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196209
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26617
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 26033
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 195754
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 4518508369 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 110040834272 (102.48 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 120878.8 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240381
telemt_connections_bad_total 5733
telemt_handshake_timeouts_total 4602
telemt_upstream_connect_attempt_total 33612
telemt_upstream_connect_success_total 33604
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34947
telemt_me_reconnect_success_total 27544
telemt_me_reader_eof_total 29659
telemt_me_idle_close_by_peer_total 29658
telemt_me_route_drop_no_conn_total 83874
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28042
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27536
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 191950
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 17483093145 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 112208442112 (104.50 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 120877.9 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330042
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 2942
telemt_upstream_connect_attempt_total 28002
telemt_upstream_connect_success_total 27970
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 28002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22095
telemt_me_reconnect_success_total 21958
telemt_me_reader_eof_total 23446
telemt_me_idle_close_by_peer_total 23445
telemt_me_route_drop_no_conn_total 116490
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303863
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1083
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22243
telemt_me_writer_restored_same_endpoint_total 21947
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 303743
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 4870010694 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 130013791060 (121.08 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 95949.5 (26h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216858
telemt_connections_bad_total 35971
telemt_handshake_timeouts_total 3617
telemt_upstream_connect_attempt_total 27433
telemt_upstream_connect_success_total 27283
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 27433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116843
telemt_me_reconnect_success_total 22352
telemt_me_reader_eof_total 23738
telemt_me_idle_close_by_peer_total 23738
telemt_me_route_drop_no_conn_total 67993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171753
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22538
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22248
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 171378
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2353888945 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 72760394099 (67.76 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 120877.5 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793189
telemt_connections_bad_total 69043
telemt_handshake_timeouts_total 7129
telemt_upstream_connect_attempt_total 25423
telemt_upstream_connect_success_total 25288
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20609
telemt_me_reconnect_success_total 19261
telemt_me_reader_eof_total 20574
telemt_me_idle_close_by_peer_total 20574
telemt_me_route_drop_no_conn_total 638685
telemt_me_route_drop_channel_closed_total 106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793611
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19530
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19234
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 652243
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 14429685316 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 392613084312 (365.65 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 78
```