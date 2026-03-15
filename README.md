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

# Server Metrics 2026-03-15 02:19:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 14718.2 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31464
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3786
telemt_upstream_connect_success_total 3763
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3009
telemt_me_reconnect_success_total 2996
telemt_me_reader_eof_total 3182
telemt_me_idle_close_by_peer_total 3182
telemt_me_route_drop_no_conn_total 9234
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29884
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3006
telemt_me_writer_restored_same_endpoint_total 2965
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 29882
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 328650244 (313.43 MB)
telemt_user_octets_to_client{user="hello"} 11586827536 (10.79 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 14725.0 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13940
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 4129
telemt_upstream_connect_success_total 4129
telemt_upstream_connect_attempts_per_request{bucket="1"} 4129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3371
telemt_me_reconnect_success_total 3356
telemt_me_reader_eof_total 3587
telemt_me_idle_close_by_peer_total 3587
telemt_me_route_drop_no_conn_total 6074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13176
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3380
telemt_me_writer_restored_same_endpoint_total 3340
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 13180
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 536563800 (511.71 MB)
telemt_user_octets_to_client{user="hello"} 2878084176 (2.68 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 14717.4 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13940
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 3965
telemt_upstream_connect_success_total 3964
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3210
telemt_me_reconnect_success_total 3193
telemt_me_reader_eof_total 3443
telemt_me_idle_close_by_peer_total 3443
telemt_me_route_drop_no_conn_total 4923
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13011
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3217
telemt_me_writer_restored_same_endpoint_total 3189
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 12970
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 8618911572 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 13701490192 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 14717.2 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15500
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 3558
telemt_upstream_connect_success_total 3557
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2807
telemt_me_reconnect_success_total 2795
telemt_me_reader_eof_total 2972
telemt_me_idle_close_by_peer_total 2972
telemt_me_route_drop_no_conn_total 5933
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14725
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2819
telemt_me_writer_restored_same_endpoint_total 2784
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 14723
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 419258144 (399.84 MB)
telemt_user_octets_to_client{user="hello"} 11930315800 (11.11 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14717.3 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17793
telemt_connections_bad_total 2939
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 4712
telemt_upstream_connect_success_total 4652
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 3961
telemt_me_reconnect_success_total 3879
telemt_me_reader_eof_total 4101
telemt_me_idle_close_by_peer_total 4101
telemt_me_route_drop_no_conn_total 5206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14118
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3894
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3867
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 14109
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 191088762 (182.24 MB)
telemt_user_octets_to_client{user="hello"} 7188127655 (6.69 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 14716.3 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46163
telemt_connections_bad_total 1159
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 3333
telemt_upstream_connect_success_total 3312
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2555
telemt_me_reconnect_success_total 2547
telemt_me_reader_eof_total 2677
telemt_me_idle_close_by_peer_total 2677
telemt_me_route_drop_no_conn_total 25354
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45102
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2541
telemt_me_writer_restored_same_endpoint_total 2520
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 43671
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1534155204 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 27935182308 (26.02 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 40
```