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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 01:34:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 24536.7 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135760
telemt_connections_bad_total 2127
telemt_handshake_timeouts_total 5168
telemt_upstream_connect_attempt_total 5174
telemt_upstream_connect_success_total 5143
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3907
telemt_me_reconnect_success_total 3893
telemt_me_reader_eof_total 4142
telemt_me_idle_close_by_peer_total 4142
telemt_me_route_drop_no_conn_total 41547
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122735
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 688
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3923
telemt_me_writer_restored_same_endpoint_total 3872
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 122662
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 1746789272 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 57363732972 (53.42 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 24788.1 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78944
telemt_connections_bad_total 983
telemt_handshake_timeouts_total 2916
telemt_upstream_connect_attempt_total 6080
telemt_upstream_connect_success_total 6003
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 6080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 4774
telemt_me_reconnect_success_total 4762
telemt_me_reader_eof_total 5036
telemt_me_idle_close_by_peer_total 5036
telemt_me_route_drop_no_conn_total 32061
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71804
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4815
telemt_me_writer_restored_same_endpoint_total 4746
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 71747
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1091033016 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 34365355780 (32.01 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 24564.3 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50236
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 1823
telemt_upstream_connect_attempt_total 6655
telemt_upstream_connect_success_total 6614
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5384
telemt_me_reconnect_success_total 5352
telemt_me_reader_eof_total 5723
telemt_me_idle_close_by_peer_total 5723
telemt_me_route_drop_no_conn_total 15418
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42259
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5415
telemt_me_writer_restored_same_endpoint_total 5341
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 42244
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5143245712 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 15661859668 (14.59 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 24623.6 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78276
telemt_connections_bad_total 3062
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 5678
telemt_upstream_connect_success_total 5626
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 5678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 4399
telemt_me_reconnect_success_total 4369
telemt_me_reader_eof_total 4632
telemt_me_idle_close_by_peer_total 4632
telemt_me_route_drop_no_conn_total 26659
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72608
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4425
telemt_me_writer_restored_same_endpoint_total 4362
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 72592
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 878979076 (838.26 MB)
telemt_user_octets_to_client{user="hello"} 31199346348 (29.06 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 24595.5 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58522
telemt_connections_bad_total 15073
telemt_handshake_timeouts_total 301
telemt_upstream_connect_attempt_total 7087
telemt_upstream_connect_success_total 6989
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 7087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_reconnect_attempts_total 6857
telemt_me_reconnect_success_total 5733
telemt_me_reader_eof_total 6007
telemt_me_idle_close_by_peer_total 6007
telemt_me_route_drop_no_conn_total 16676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5870
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 41417
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 319025000 (304.25 MB)
telemt_user_octets_to_client{user="hello"} 13735397420 (12.79 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 24756.4 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145451
telemt_connections_bad_total 4533
telemt_handshake_timeouts_total 1007
telemt_upstream_connect_attempt_total 5112
telemt_upstream_connect_success_total 5083
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 5112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3850
telemt_me_reconnect_success_total 3837
telemt_me_reader_eof_total 4107
telemt_me_idle_close_by_peer_total 4107
telemt_me_route_drop_no_conn_total 169844
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212633
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3890
telemt_me_writer_restored_same_endpoint_total 3827
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 134894
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 2256584596 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 112429647152 (104.71 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12763.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 6131
telemt_upstream_connect_success_total 6130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5456
telemt_me_reconnect_success_total 5424
telemt_me_reader_eof_total 5941
telemt_me_idle_close_by_peer_total 5941
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5479
telemt_me_writer_restored_same_endpoint_total 5424
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```