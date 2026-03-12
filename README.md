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

# Server Metrics 2026-03-12 12:27:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17672.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94056
telemt_connections_bad_total 530
telemt_handshake_timeouts_total 3385
telemt_upstream_connect_attempt_total 4339
telemt_upstream_connect_success_total 4319
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 3420
telemt_me_reconnect_success_total 3399
telemt_me_reader_eof_total 3549
telemt_me_idle_close_by_peer_total 3548
telemt_me_route_drop_no_conn_total 26250
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3420
telemt_me_writer_restored_same_endpoint_total 3383
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 84580
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 1167435512 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 27150672712 (25.29 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17565.3 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37883
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 305
telemt_upstream_connect_attempt_total 5397
telemt_upstream_connect_success_total 5266
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 5397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 18808
telemt_me_reconnect_success_total 4361
telemt_me_reader_eof_total 4855
telemt_me_idle_close_by_peer_total 4855
telemt_me_route_drop_no_conn_total 16399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36062
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4828
telemt_me_refill_failed_total 451
telemt_me_writer_restored_same_endpoint_total 4346
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 36063
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 411843344 (392.76 MB)
telemt_user_octets_to_client{user="hello"} 9456552268 (8.81 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17528.8 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51267
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 4852
telemt_upstream_connect_success_total 4852
telemt_upstream_connect_attempts_per_request{bucket="1"} 4852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3951
telemt_me_reconnect_success_total 3922
telemt_me_reader_eof_total 4128
telemt_me_idle_close_by_peer_total 4128
telemt_me_route_drop_no_conn_total 17883
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48279
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3941
telemt_me_writer_restored_same_endpoint_total 3902
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 48263
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1538170844 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 31380728868 (29.23 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17504.6 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65146
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 4747
telemt_upstream_connect_success_total 4635
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 4747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 10257
telemt_me_reconnect_success_total 3714
telemt_me_reader_eof_total 4041
telemt_me_idle_close_by_peer_total 4041
telemt_me_route_drop_no_conn_total 21936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59644
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3965
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3706
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 59642
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1054651076 (1005.79 MB)
telemt_user_octets_to_client{user="hello"} 29784232496 (27.74 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17473.9 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35781
telemt_connections_bad_total 3308
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 5145
telemt_upstream_connect_success_total 4929
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 5145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 21741
telemt_me_reconnect_success_total 3560
telemt_me_reader_eof_total 4125
telemt_me_idle_close_by_peer_total 4125
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 10988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30511
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 380
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4149
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 3543
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 30961
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 218366329 (208.25 MB)
telemt_user_octets_to_client{user="hello"} 7768586594 (7.24 GB)
telemt_user_msgs_from_client{user="hello"} 5716
telemt_user_msgs_to_client{user="hello"} 12832
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17460.7 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97733
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 912
telemt_upstream_connect_attempt_total 3515
telemt_upstream_connect_success_total 3498
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 2614
telemt_me_reconnect_success_total 2591
telemt_me_reader_eof_total 2731
telemt_me_idle_close_by_peer_total 2731
telemt_me_route_drop_no_conn_total 40369
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92877
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2623
telemt_me_writer_restored_same_endpoint_total 2584
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 92844
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 2408797356 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 45489811780 (42.37 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 39
```