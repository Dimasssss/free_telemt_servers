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

# Server Metrics 2026-03-12 09:44:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7854.7 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41556
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 2082
telemt_upstream_connect_attempt_total 1914
telemt_upstream_connect_success_total 1906
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1505
telemt_me_idle_close_by_peer_total 1505
telemt_me_route_drop_no_conn_total 11069
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37050
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1485
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 37027
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 604277768 (576.28 MB)
telemt_user_octets_to_client{user="hello"} 10597799788 (9.87 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7747.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17013
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 2820
telemt_upstream_connect_success_total 2768
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 5142
telemt_me_reconnect_success_total 2352
telemt_me_reader_eof_total 2463
telemt_me_idle_close_by_peer_total 2463
telemt_me_route_drop_no_conn_total 5880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16192
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2433
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2337
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 16188
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 101904392 (97.18 MB)
telemt_user_octets_to_client{user="hello"} 3131848628 (2.92 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7711.6 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23636
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 1982
telemt_upstream_connect_success_total 1982
telemt_upstream_connect_attempts_per_request{bucket="1"} 1982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1570
telemt_me_reconnect_success_total 1562
telemt_me_reader_eof_total 1624
telemt_me_idle_close_by_peer_total 1624
telemt_me_route_drop_no_conn_total 7652
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21870
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1546
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 21866
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 238751280 (227.69 MB)
telemt_user_octets_to_client{user="hello"} 24016992840 (22.37 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7686.9 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26334
telemt_connections_bad_total 1027
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 2203
telemt_upstream_connect_success_total 2145
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 2203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1750
telemt_me_reconnect_success_total 1719
telemt_me_reader_eof_total 1775
telemt_me_idle_close_by_peer_total 1775
telemt_me_route_drop_no_conn_total 7892
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23498
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_restored_same_endpoint_total 1711
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 23497
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 634309144 (604.92 MB)
telemt_user_octets_to_client{user="hello"} 8644646512 (8.05 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7656.5 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14803
telemt_connections_bad_total 1517
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 2204
telemt_upstream_connect_success_total 2112
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 2204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8100
telemt_me_reconnect_success_total 1689
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1873
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 4286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12788
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 227
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1892
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 12787
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 59026972 (56.29 MB)
telemt_user_octets_to_client{user="hello"} 3497232832 (3.26 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7643.3 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36879
telemt_connections_bad_total 530
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 1417
telemt_upstream_connect_success_total 1407
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1000
telemt_me_reconnect_success_total 992
telemt_me_reader_eof_total 1034
telemt_me_idle_close_by_peer_total 1034
telemt_me_route_drop_no_conn_total 16646
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34437
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 34402
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 1578326224 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 22269378092 (20.74 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 43
```