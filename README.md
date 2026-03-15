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

# Server Metrics 2026-03-15 02:50:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 16550.6 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36399
telemt_connections_bad_total 373
telemt_handshake_timeouts_total 285
telemt_upstream_connect_attempt_total 4245
telemt_upstream_connect_success_total 4218
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3378
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3579
telemt_me_idle_close_by_peer_total 3579
telemt_me_route_drop_no_conn_total 10834
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34587
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 177
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3377
telemt_me_writer_restored_same_endpoint_total 3333
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 34585
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 372915628 (355.64 MB)
telemt_user_octets_to_client{user="hello"} 12430321020 (11.58 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 16557.2 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14809
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 4658
telemt_upstream_connect_success_total 4658
telemt_upstream_connect_attempts_per_request{bucket="1"} 4658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3813
telemt_me_reconnect_success_total 3796
telemt_me_reader_eof_total 4060
telemt_me_idle_close_by_peer_total 4060
telemt_me_route_drop_no_conn_total 7008
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14006
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3821
telemt_me_writer_restored_same_endpoint_total 3780
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 14010
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 577309444 (550.57 MB)
telemt_user_octets_to_client{user="hello"} 3570812128 (3.33 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 16549.7 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15395
telemt_connections_bad_total 285
telemt_handshake_timeouts_total 264
telemt_upstream_connect_attempt_total 4486
telemt_upstream_connect_success_total 4485
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3645
telemt_me_reconnect_success_total 3626
telemt_me_reader_eof_total 3908
telemt_me_idle_close_by_peer_total 3908
telemt_me_route_drop_no_conn_total 5336
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14361
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3652
telemt_me_writer_restored_same_endpoint_total 3622
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 14319
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 8639536708 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 13782061220 (12.84 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 16549.4 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17454
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 4021
telemt_upstream_connect_success_total 4020
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3183
telemt_me_reconnect_success_total 3170
telemt_me_reader_eof_total 3379
telemt_me_idle_close_by_peer_total 3379
telemt_me_route_drop_no_conn_total 6670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16549
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3199
telemt_me_writer_restored_same_endpoint_total 3159
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 16547
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 426806808 (407.03 MB)
telemt_user_octets_to_client{user="hello"} 12071477740 (11.24 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 16549.7 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19350
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 5224
telemt_upstream_connect_success_total 5159
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 5224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 4382
telemt_me_reconnect_success_total 4299
telemt_me_reader_eof_total 4557
telemt_me_idle_close_by_peer_total 4557
telemt_me_route_drop_no_conn_total 5612
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15311
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4318
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 4287
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 15302
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 196670934 (187.56 MB)
telemt_user_octets_to_client{user="hello"} 7444705935 (6.93 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 16548.7 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51114
telemt_connections_bad_total 1204
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 3727
telemt_upstream_connect_success_total 3706
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2863
telemt_me_reconnect_success_total 2853
telemt_me_reader_eof_total 3006
telemt_me_idle_close_by_peer_total 3006
telemt_me_route_drop_no_conn_total 27718
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49745
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2850
telemt_me_writer_restored_same_endpoint_total 2826
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 48314
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1666676304 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 29262255060 (27.25 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 23
```