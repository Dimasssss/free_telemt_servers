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

# Server Metrics 2026-03-14 16:48:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 12739.2 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72728
telemt_connections_bad_total 12379
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 3168
telemt_upstream_connect_success_total 3166
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 2484
telemt_me_reconnect_success_total 2455
telemt_me_reader_eof_total 2578
telemt_me_idle_close_by_peer_total 2578
telemt_me_route_drop_no_conn_total 26675
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57900
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2503
telemt_me_writer_restored_same_endpoint_total 2437
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 57832
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 1143296536 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 25610095500 (23.85 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 12737.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29838
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 631
telemt_upstream_connect_attempt_total 3603
telemt_upstream_connect_success_total 3572
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 5430
telemt_me_reconnect_success_total 2861
telemt_me_reader_eof_total 3032
telemt_me_idle_close_by_peer_total 3032
telemt_me_route_drop_no_conn_total 15218
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27817
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2987
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2856
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 27799
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 340787828 (325.00 MB)
telemt_user_octets_to_client{user="hello"} 10806798316 (10.06 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 12742.5 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30230
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 1578
telemt_upstream_connect_attempt_total 5300
telemt_upstream_connect_success_total 5249
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 99450
telemt_me_reconnect_success_total 4222
telemt_me_reader_eof_total 4427
telemt_me_idle_close_by_peer_total 4427
telemt_me_route_drop_no_conn_total 11443
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26461
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4394
telemt_me_refill_failed_total 3087
telemt_me_writer_restored_same_endpoint_total 4184
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 26751
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2745333577 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 13851786738 (12.90 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 12747.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39548
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 243
telemt_upstream_connect_attempt_total 3505
telemt_upstream_connect_success_total 3488
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 2803
telemt_me_reconnect_success_total 2786
telemt_me_reader_eof_total 2892
telemt_me_idle_close_by_peer_total 2892
telemt_me_route_drop_no_conn_total 19099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37766
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2812
telemt_me_writer_restored_same_endpoint_total 2784
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 37647
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 405133160 (386.37 MB)
telemt_user_octets_to_client{user="hello"} 12648857768 (11.78 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 12740.4 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28163
telemt_connections_bad_total 2513
telemt_handshake_timeouts_total 1346
telemt_upstream_connect_attempt_total 2953
telemt_upstream_connect_success_total 2915
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 2953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 8725
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 2451
telemt_me_idle_close_by_peer_total 2451
telemt_me_route_drop_no_conn_total 9923
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23041
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2422
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2202
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 23036
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 202799616 (193.40 MB)
telemt_user_octets_to_client{user="hello"} 6727071308 (6.27 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 12739.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101529
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1117
telemt_upstream_connect_attempt_total 2670
telemt_upstream_connect_success_total 2616
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 2670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 6898
telemt_me_reconnect_success_total 1903
telemt_me_reader_eof_total 2089
telemt_me_idle_close_by_peer_total 2089
telemt_me_route_drop_no_conn_total 51061
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91665
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2076
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 91560
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 1516924980 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 43826243616 (40.82 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 69
```