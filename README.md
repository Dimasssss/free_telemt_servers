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

# Server Metrics 2026-03-12 09:28:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6930.8 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37258
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 1550
telemt_upstream_connect_success_total 1544
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 1187
telemt_me_idle_close_by_peer_total 1187
telemt_me_route_drop_no_conn_total 9803
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1167
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 32872
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 455012704 (433.93 MB)
telemt_user_octets_to_client{user="hello"} 9709474680 (9.04 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6824.0 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14545
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 2486
telemt_upstream_connect_success_total 2437
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 4854
telemt_me_reconnect_success_total 2065
telemt_me_reader_eof_total 2144
telemt_me_idle_close_by_peer_total 2144
telemt_me_route_drop_no_conn_total 5240
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13898
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2144
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2050
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 13894
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 81333120 (77.57 MB)
telemt_user_octets_to_client{user="hello"} 2552480092 (2.38 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6788.2 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21009
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 1762
telemt_upstream_connect_success_total 1762
telemt_upstream_connect_attempts_per_request{bucket="1"} 1762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1393
telemt_me_reconnect_success_total 1386
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1436
telemt_me_route_drop_no_conn_total 6898
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19577
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_restored_same_endpoint_total 1366
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 19573
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 214403332 (204.47 MB)
telemt_user_octets_to_client{user="hello"} 21516322568 (20.04 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6763.3 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23812
telemt_connections_bad_total 1027
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 1929
telemt_upstream_connect_success_total 1877
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1525
telemt_me_reconnect_success_total 1496
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 7027
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21179
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1517
telemt_me_writer_restored_same_endpoint_total 1488
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 21178
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 612519636 (584.14 MB)
telemt_user_octets_to_client{user="hello"} 7539839036 (7.02 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6732.6 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12881
telemt_connections_bad_total 1335
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 2021
telemt_upstream_connect_success_total 1933
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 2021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 7964
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1735
telemt_me_idle_close_by_peer_total 1735
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 3668
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11098
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 190
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1758
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 1544
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 11097
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 50914720 (48.56 MB)
telemt_user_octets_to_client{user="hello"} 2742135680 (2.55 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6719.6 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32383
telemt_connections_bad_total 528
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 1215
telemt_upstream_connect_success_total 1207
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 844
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 14433
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30195
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_restored_same_endpoint_total 829
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 30162
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1532963684 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 19707428796 (18.35 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 46
```