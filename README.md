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

# Server Metrics 2026-03-15 15:23:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 61768.2 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281129
telemt_connections_bad_total 2761
telemt_handshake_timeouts_total 8447
telemt_upstream_connect_attempt_total 15496
telemt_upstream_connect_success_total 15414
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15708
telemt_me_reconnect_success_total 12326
telemt_me_reader_eof_total 13128
telemt_me_idle_close_by_peer_total 13128
telemt_me_route_drop_no_conn_total 446051
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319786
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1743
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12561
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12292
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 258889
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 5660157744 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 218641152716 (203.63 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 61775.0 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105687
telemt_connections_bad_total 2805
telemt_handshake_timeouts_total 9936
telemt_upstream_connect_attempt_total 17066
telemt_upstream_connect_success_total 17066
telemt_upstream_connect_attempts_per_request{bucket="1"} 17066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16293
telemt_me_reconnect_success_total 13935
telemt_me_reader_eof_total 14895
telemt_me_idle_close_by_peer_total 14895
telemt_me_route_drop_no_conn_total 44181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89724
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 14172
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13919
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 89711
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 1820301432 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 45008492612 (41.92 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 61767.4 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114398
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 2883
telemt_upstream_connect_attempt_total 18250
telemt_upstream_connect_success_total 18242
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22446
telemt_me_reconnect_success_total 15099
telemt_me_reader_eof_total 16219
telemt_me_idle_close_by_peer_total 16219
telemt_me_route_drop_no_conn_total 43885
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15465
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15091
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 98982
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 10325224976 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 57383343356 (53.44 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 61767.3 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151252
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 956
telemt_upstream_connect_attempt_total 14868
telemt_upstream_connect_success_total 14864
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11843
telemt_me_reconnect_success_total 11772
telemt_me_reader_eof_total 12517
telemt_me_idle_close_by_peer_total 12517
telemt_me_route_drop_no_conn_total 58924
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138636
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11909
telemt_me_writer_restored_same_endpoint_total 11761
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 138549
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2652046356 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 66314885092 (61.76 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 36838.6 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89310
telemt_connections_bad_total 22033
telemt_handshake_timeouts_total 1797
telemt_upstream_connect_attempt_total 11425
telemt_upstream_connect_success_total 11357
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103774
telemt_me_reconnect_success_total 9341
telemt_me_reader_eof_total 9774
telemt_me_idle_close_by_peer_total 9774
telemt_me_route_drop_no_conn_total 30463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63449
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 9371
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9237
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 63585
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 895187861 (853.72 MB)
telemt_user_octets_to_client{user="hello"} 27176410591 (25.31 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 61767.1 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381614
telemt_connections_bad_total 49853
telemt_handshake_timeouts_total 3300
telemt_upstream_connect_attempt_total 13273
telemt_upstream_connect_success_total 13195
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 13273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11372
telemt_me_reconnect_success_total 10076
telemt_me_reader_eof_total 10721
telemt_me_idle_close_by_peer_total 10721
telemt_me_route_drop_no_conn_total 204095
telemt_me_route_drop_channel_closed_total 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329219
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10217
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10049
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 314786
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 8063860128 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 166280203100 (154.86 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 70
```