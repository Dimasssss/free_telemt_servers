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

# Server Metrics 2026-03-16 15:18:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 6058.9 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69175
telemt_connections_bad_total 416
telemt_handshake_timeouts_total 1754
telemt_upstream_connect_attempt_total 1316
telemt_upstream_connect_success_total 1314
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 974
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 19916
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64356
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 962
telemt_me_writer_restored_same_endpoint_total 964
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 64287
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 1426843848 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 38334185200 (35.70 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 838.0 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7957
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 4241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7608
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_user_connections_total{user="hello"} 7602
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 77846844 (74.24 MB)
telemt_user_octets_to_client{user="hello"} 1371030116 (1.28 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 6173.0 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28359
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 437
telemt_upstream_connect_attempt_total 2426
telemt_upstream_connect_success_total 2391
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 34792
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1208
telemt_me_idle_close_by_peer_total 1208
telemt_me_route_drop_no_conn_total 7849
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24999
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 1231
telemt_me_refill_failed_total 1053
telemt_me_writer_restored_same_endpoint_total 1029
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 25949
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 311185082 (296.77 MB)
telemt_user_octets_to_client{user="hello"} 4276103638 (3.98 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 6308.9 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50379
telemt_connections_bad_total 116
telemt_handshake_timeouts_total 836
telemt_upstream_connect_attempt_total 1290
telemt_upstream_connect_success_total 1282
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 5860
telemt_me_reconnect_success_total 912
telemt_me_reader_eof_total 1042
telemt_me_idle_close_by_peer_total 1042
telemt_me_route_drop_no_conn_total 17412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47578
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_me_writer_removed_unexpected_total 1066
telemt_me_refill_failed_total 154
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 47559
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 841695044 (802.70 MB)
telemt_user_octets_to_client{user="hello"} 11029432232 (10.27 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 3769.5 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20097
telemt_connections_bad_total 7200
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 1030
telemt_upstream_connect_success_total 1016
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 776
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 756
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 4526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12166
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 12150
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 274148452 (261.45 MB)
telemt_user_octets_to_client{user="hello"} 2129434112 (1.98 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 5876.8 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70579
telemt_connections_bad_total 1133
telemt_handshake_timeouts_total 1514
telemt_upstream_connect_attempt_total 1216
telemt_upstream_connect_success_total 1216
telemt_upstream_connect_attempts_per_request{bucket="1"} 1216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3245
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 31697
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66012
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 948
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 65766
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 1437008724 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 19137347212 (17.82 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 77
```