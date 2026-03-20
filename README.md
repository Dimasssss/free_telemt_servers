# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 06:09:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 46306.9 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912162
telemt_connections_bad_total 57580
telemt_connections_current 1275
telemt_connections_me_current 1275
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23482
telemt_upstream_connect_attempt_total 9020
telemt_upstream_connect_success_total 8916
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 9020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5538
telemt_me_reconnect_success_total 5494
telemt_me_reader_eof_total 5817
telemt_me_idle_close_by_peer_total 5816
telemt_me_route_drop_no_conn_total 255695
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737059
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3920
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 2508
telemt_desync_frames_bucket_total{bucket="1_2"} 755
telemt_desync_frames_bucket_total{bucket="3_10"} 1536
telemt_desync_frames_bucket_total{bucket="gt_10"} 1629
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 5551
telemt_me_writer_restored_same_endpoint_total 5481
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 738613
telemt_user_connections_current{user="hello"} 1275
telemt_user_octets_from_client{user="hello"} 33585830024 (31.28 GB)
telemt_user_octets_to_client{user="hello"} 256399902357 (238.79 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 62762.4 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4015787
telemt_connections_bad_total 363101
telemt_connections_current 5071
telemt_connections_me_current 5071
telemt_handshake_timeouts_total 95575
telemt_upstream_connect_attempt_total 11763
telemt_upstream_connect_success_total 11544
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 11763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11464
telemt_me_reconnect_success_total 7211
telemt_me_reader_eof_total 7714
telemt_me_idle_close_by_peer_total 7713
telemt_me_route_drop_no_conn_total 1798870
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3285161
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13273
telemt_desync_full_logged_total 4421
telemt_desync_suppressed_total 8852
telemt_desync_frames_bucket_total{bucket="1_2"} 2567
telemt_desync_frames_bucket_total{bucket="3_10"} 5173
telemt_desync_frames_bucket_total{bucket="gt_10"} 5533
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 7435
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7156
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 3284797
telemt_user_connections_current{user="hello"} 5071
telemt_user_octets_from_client{user="hello"} 49027249390 (45.66 GB)
telemt_user_octets_to_client{user="hello"} 1242459388398 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 62740.5 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3593173
telemt_connections_bad_total 506304
telemt_connections_current 3834
telemt_connections_me_current 3834
telemt_handshake_timeouts_total 55071
telemt_upstream_connect_attempt_total 10106
telemt_upstream_connect_success_total 10036
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 10106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7874
telemt_me_reconnect_success_total 6929
telemt_me_reader_eof_total 7305
telemt_me_idle_close_by_peer_total 7304
telemt_me_route_drop_no_conn_total 2104974
telemt_me_route_drop_channel_closed_total 190
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2530461
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9274
telemt_desync_full_logged_total 2892
telemt_desync_suppressed_total 6382
telemt_desync_frames_bucket_total{bucket="1_2"} 2316
telemt_desync_frames_bucket_total{bucket="3_10"} 3537
telemt_desync_frames_bucket_total{bucket="gt_10"} 3421
telemt_pool_swap_total 63
telemt_me_writer_close_signal_drop_total 80
telemt_me_writer_removed_unexpected_total 7006
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6928
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 2525516
telemt_user_connections_current{user="hello"} 3834
telemt_user_octets_from_client{user="hello"} 38060262600 (35.45 GB)
telemt_user_octets_to_client{user="hello"} 1034789055712 (963.72 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 62728.0 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3524896
telemt_connections_bad_total 253583
telemt_connections_current 3964
telemt_connections_me_current 3964
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 52574
telemt_upstream_connect_attempt_total 67505
telemt_upstream_connect_success_total 62783
telemt_upstream_connect_fail_total 4722
telemt_upstream_connect_attempts_per_request{bucket="1"} 67505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4722
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10246
telemt_me_reconnect_success_total 7270
telemt_me_reader_eof_total 7585
telemt_me_idle_close_by_peer_total 7584
telemt_me_route_drop_no_conn_total 2865873
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2883989
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10550
telemt_desync_full_logged_total 3247
telemt_desync_suppressed_total 7303
telemt_desync_frames_bucket_total{bucket="1_2"} 2470
telemt_desync_frames_bucket_total{bucket="3_10"} 3980
telemt_desync_frames_bucket_total{bucket="gt_10"} 4100
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 675
telemt_me_writer_removed_unexpected_total 7988
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7266
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2934571
telemt_user_connections_current{user="hello"} 3964
telemt_user_octets_from_client{user="hello"} 42619082860 (39.69 GB)
telemt_user_octets_to_client{user="hello"} 804485560763 (749.24 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1182
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 311.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45517
telemt_connections_bad_total 1405
telemt_connections_current 4175
telemt_connections_me_current 4175
telemt_handshake_timeouts_total 1008
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 127
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 32094
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39945
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 27
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 39796
telemt_user_connections_current{user="hello"} 4175
telemt_user_octets_from_client{user="hello"} 331055896 (315.72 MB)
telemt_user_octets_to_client{user="hello"} 7691440480 (7.16 GB)
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 246.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4741
telemt_connections_bad_total 21
telemt_connections_current 396
telemt_connections_me_current 396
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_route_drop_no_conn_total 743
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4322
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 4319
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 27807460 (26.52 MB)
telemt_user_octets_to_client{user="hello"} 980511312 (935.09 MB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 62692.6 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623475
telemt_connections_bad_total 164163
telemt_connections_current 3710
telemt_connections_me_current 3710
telemt_handshake_timeouts_total 46773
telemt_upstream_connect_attempt_total 11157
telemt_upstream_connect_success_total 11089
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 8028
telemt_me_reconnect_success_total 7977
telemt_me_reader_eof_total 8433
telemt_me_idle_close_by_peer_total 8433
telemt_me_route_drop_no_conn_total 905484
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2196110
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10945
telemt_desync_full_logged_total 3601
telemt_desync_suppressed_total 7344
telemt_desync_frames_bucket_total{bucket="1_2"} 2125
telemt_desync_frames_bucket_total{bucket="3_10"} 3868
telemt_desync_frames_bucket_total{bucket="gt_10"} 4952
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8088
telemt_me_writer_restored_same_endpoint_total 7960
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2194907
telemt_user_connections_current{user="hello"} 3710
telemt_user_octets_from_client{user="hello"} 48172984740 (44.86 GB)
telemt_user_octets_to_client{user="hello"} 1158294152796 (1.05 TB)
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 451
```