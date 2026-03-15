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

# Server Metrics 2026-03-15 19:03:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 74936.4 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352155
telemt_connections_bad_total 4276
telemt_handshake_timeouts_total 12717
telemt_upstream_connect_attempt_total 18112
telemt_upstream_connect_success_total 18020
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 18112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17665
telemt_me_reconnect_success_total 14266
telemt_me_reader_eof_total 15205
telemt_me_idle_close_by_peer_total 15205
telemt_me_route_drop_no_conn_total 470079
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382802
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1920
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14528
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14232
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 321865
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 6860471808 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 248756825504 (231.67 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 74943.0 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142617
telemt_connections_bad_total 2843
telemt_handshake_timeouts_total 12720
telemt_upstream_connect_attempt_total 20184
telemt_upstream_connect_success_total 20183
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 18757
telemt_me_reconnect_success_total 16382
telemt_me_reader_eof_total 17513
telemt_me_idle_close_by_peer_total 17512
telemt_me_route_drop_no_conn_total 59729
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121308
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16684
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16366
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 121288
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2317300200 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 60240838780 (56.10 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 74935.3 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145636
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 3326
telemt_upstream_connect_attempt_total 21765
telemt_upstream_connect_success_total 21757
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25309
telemt_me_reconnect_success_total 17947
telemt_me_reader_eof_total 19272
telemt_me_idle_close_by_peer_total 19272
telemt_me_route_drop_no_conn_total 56917
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 18352
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17939
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 128435
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 10793338204 (10.05 GB)
telemt_user_octets_to_client{user="hello"} 70099612992 (65.29 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 74935.0 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204043
telemt_connections_bad_total 1113
telemt_handshake_timeouts_total 1441
telemt_upstream_connect_attempt_total 17676
telemt_upstream_connect_success_total 17662
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13996
telemt_me_reconnect_success_total 13912
telemt_me_reader_eof_total 14813
telemt_me_idle_close_by_peer_total 14813
telemt_me_route_drop_no_conn_total 76120
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188092
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 677
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14078
telemt_me_writer_restored_same_endpoint_total 13901
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 188010
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 3559584800 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 87077586004 (81.10 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 50006.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123054
telemt_connections_bad_total 24936
telemt_handshake_timeouts_total 2473
telemt_upstream_connect_attempt_total 14787
telemt_upstream_connect_success_total 14698
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 14787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106463
telemt_me_reconnect_success_total 12016
telemt_me_reader_eof_total 12615
telemt_me_idle_close_by_peer_total 12615
telemt_me_route_drop_no_conn_total 42378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92234
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 12092
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11912
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 92364
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1523955845 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 35503725479 (33.07 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 74935.1 (20h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505773
telemt_connections_bad_total 57965
telemt_handshake_timeouts_total 4089
telemt_upstream_connect_attempt_total 16062
telemt_upstream_connect_success_total 15970
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13497
telemt_me_reconnect_success_total 12191
telemt_me_reader_eof_total 12956
telemt_me_idle_close_by_peer_total 12956
telemt_me_route_drop_no_conn_total 324344
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467350
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12361
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12164
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 425121
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 10917066048 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 233960732388 (217.89 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 61
```