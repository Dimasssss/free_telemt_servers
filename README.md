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

# Server Metrics 2026-03-13 07:02:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 84562.9 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321597
telemt_connections_bad_total 3141
telemt_handshake_timeouts_total 6740
telemt_upstream_connect_attempt_total 21249
telemt_upstream_connect_success_total 21151
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1640
telemt_me_reconnect_attempts_total 20425
telemt_me_reconnect_success_total 16922
telemt_me_reader_eof_total 18093
telemt_me_idle_close_by_peer_total 18092
telemt_me_route_drop_no_conn_total 101052
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272918
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17213
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16906
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 272620
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 4590136524 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 129399448140 (120.51 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 84455.5 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147211
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1143
telemt_upstream_connect_attempt_total 43848
telemt_upstream_connect_success_total 43276
telemt_upstream_connect_fail_total 572
telemt_upstream_connect_attempts_per_request{bucket="1"} 43848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 572
telemt_me_keepalive_timeout_total 643
telemt_me_reconnect_attempts_total 71761
telemt_me_reconnect_success_total 22567
telemt_me_reader_eof_total 24782
telemt_me_idle_close_by_peer_total 24782
telemt_me_route_drop_no_conn_total 55556
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122819
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 24281
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 22552
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 139314
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1437192812 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 45236337395 (42.13 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 84419.1 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178441
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2904
telemt_upstream_connect_attempt_total 23025
telemt_upstream_connect_success_total 23023
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 509
telemt_me_reconnect_attempts_total 19949
telemt_me_reconnect_success_total 18775
telemt_me_reader_eof_total 20125
telemt_me_idle_close_by_peer_total 20125
telemt_me_route_drop_no_conn_total 68810
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166979
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18977
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18755
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 166907
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2991834852 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 73763292536 (68.70 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 84394.8 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256449
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1954
telemt_upstream_connect_attempt_total 35674
telemt_upstream_connect_success_total 25733
telemt_upstream_connect_fail_total 9941
telemt_upstream_connect_attempts_per_request{bucket="1"} 35674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9941
telemt_me_keepalive_timeout_total 3354
telemt_me_reconnect_attempts_total 70206
telemt_me_reconnect_success_total 18667
telemt_me_reader_eof_total 20853
telemt_me_idle_close_by_peer_total 20846
telemt_me_route_drop_no_conn_total 92745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216481
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 661
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20519
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18657
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1852
telemt_user_connections_total{user="hello"} 219215
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 4456586018 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 84396308081 (78.60 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34566.3 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40930
telemt_connections_bad_total 7148
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 11816
telemt_upstream_connect_success_total 11698
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 11816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 10921
telemt_me_reconnect_success_total 9954
telemt_me_reader_eof_total 10623
telemt_me_idle_close_by_peer_total 10623
telemt_me_route_drop_no_conn_total 11591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10073
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9936
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 32578
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 241531820 (230.34 MB)
telemt_user_octets_to_client{user="hello"} 10535535016 (9.81 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84351.1 (23h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434811
telemt_connections_bad_total 8906
telemt_handshake_timeouts_total 3287
telemt_upstream_connect_attempt_total 17956
telemt_upstream_connect_success_total 17859
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1467
telemt_me_reconnect_attempts_total 17310
telemt_me_reconnect_success_total 13674
telemt_me_reader_eof_total 14685
telemt_me_idle_close_by_peer_total 14682
telemt_me_route_drop_no_conn_total 192194
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419754
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13959
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13667
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 407985
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 6591342956 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 236042470408 (219.83 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 62
```