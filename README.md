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

# Server Metrics 2026-03-14 15:26:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 7832.4 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45106
telemt_connections_bad_total 7961
telemt_handshake_timeouts_total 230
telemt_upstream_connect_attempt_total 2055
telemt_upstream_connect_success_total 2053
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 1633
telemt_me_reconnect_success_total 1611
telemt_me_reader_eof_total 1673
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 17426
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35850
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1645
telemt_me_writer_restored_same_endpoint_total 1593
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 35786
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 600738388 (572.91 MB)
telemt_user_octets_to_client{user="hello"} 12680467184 (11.81 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 7830.3 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18006
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 2229
telemt_upstream_connect_success_total 2202
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 4324
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 9526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16886
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1874
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1763
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 16869
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 217538904 (207.46 MB)
telemt_user_octets_to_client{user="hello"} 5047534628 (4.70 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 7835.0 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17539
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 419
telemt_upstream_connect_attempt_total 3501
telemt_upstream_connect_success_total 3473
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 96598
telemt_me_reconnect_success_total 2719
telemt_me_reader_eof_total 2855
telemt_me_idle_close_by_peer_total 2855
telemt_me_route_drop_no_conn_total 7012
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15713
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2841
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2681
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 16006
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 511131677 (487.45 MB)
telemt_user_octets_to_client{user="hello"} 7364767746 (6.86 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 7839.8 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24904
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 2146
telemt_upstream_connect_success_total 2136
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 1714
telemt_me_reconnect_success_total 1701
telemt_me_reader_eof_total 1734
telemt_me_idle_close_by_peer_total 1734
telemt_me_route_drop_no_conn_total 11885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23638
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1710
telemt_me_writer_restored_same_endpoint_total 1699
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 23520
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 277751512 (264.88 MB)
telemt_user_octets_to_client{user="hello"} 9257557656 (8.62 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 7832.8 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17126
telemt_connections_bad_total 1597
telemt_handshake_timeouts_total 230
telemt_upstream_connect_attempt_total 1729
telemt_upstream_connect_success_total 1702
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1015
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7772
telemt_me_reconnect_success_total 1265
telemt_me_reader_eof_total 1449
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 6156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14432
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1465
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1261
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 14428
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 117653860 (112.20 MB)
telemt_user_octets_to_client{user="hello"} 3719575776 (3.46 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 7832.2 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61708
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 1752
telemt_upstream_connect_success_total 1714
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 1752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1304
telemt_me_reconnect_success_total 1274
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 31004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57147
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1285
telemt_me_writer_restored_same_endpoint_total 1270
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 57053
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 995262824 (949.16 MB)
telemt_user_octets_to_client{user="hello"} 22207904808 (20.68 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 68
```