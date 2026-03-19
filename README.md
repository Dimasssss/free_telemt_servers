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

# Server Metrics 2026-03-19 04:05:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 22643.0 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293273
telemt_connections_bad_total 33239
telemt_connections_current 932
telemt_connections_me_current 932
telemt_handshake_timeouts_total 18742
telemt_upstream_connect_attempt_total 4474
telemt_upstream_connect_success_total 4404
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3264
telemt_me_reconnect_success_total 3248
telemt_me_reader_eof_total 3410
telemt_me_idle_close_by_peer_total 3410
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 77513
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222713
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1155
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3271
telemt_me_writer_restored_same_endpoint_total 3231
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 219961
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 2462089296 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 65503750876 (61.01 GB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 22646.4 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549244
telemt_connections_bad_total 38533
telemt_connections_current 2393
telemt_connections_me_current 2393
telemt_handshake_timeouts_total 15264
telemt_upstream_connect_attempt_total 4287
telemt_upstream_connect_success_total 4209
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 3060
telemt_me_reconnect_success_total 3044
telemt_me_reader_eof_total 3210
telemt_me_idle_close_by_peer_total 3210
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 164009
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451974
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1704
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3093
telemt_me_writer_restored_same_endpoint_total 3026
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 451925
telemt_user_connections_current{user="hello"} 2393
telemt_user_octets_from_client{user="hello"} 13367115000 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 197451858820 (183.89 GB)
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 22696.7 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547490
telemt_connections_bad_total 65284
telemt_connections_current 1582
telemt_connections_me_current 1582
telemt_handshake_timeouts_total 10805
telemt_upstream_connect_attempt_total 4120
telemt_upstream_connect_success_total 4120
telemt_upstream_connect_attempts_per_request{bucket="1"} 4120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2972
telemt_me_reconnect_success_total 2961
telemt_me_reader_eof_total 3123
telemt_me_idle_close_by_peer_total 3122
telemt_me_route_drop_no_conn_total 136750
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329469
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 915
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2995
telemt_me_writer_restored_same_endpoint_total 2937
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 329221
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 4021984080 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 123332319084 (114.86 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 22640.1 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589549
telemt_connections_bad_total 146746
telemt_connections_current 1843
telemt_connections_me_current 1843
telemt_handshake_timeouts_total 18018
telemt_upstream_connect_attempt_total 4252
telemt_upstream_connect_success_total 4224
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3075
telemt_me_reconnect_success_total 3057
telemt_me_reader_eof_total 3228
telemt_me_idle_close_by_peer_total 3228
telemt_me_route_drop_no_conn_total 150309
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358783
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1557
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 956
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3084
telemt_me_writer_restored_same_endpoint_total 3033
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 358699
telemt_user_connections_current{user="hello"} 1843
telemt_user_octets_from_client{user="hello"} 10934533412 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 206756531552 (192.56 GB)
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 22651.8 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109484
telemt_connections_bad_total 10209
telemt_connections_current 486
telemt_connections_me_current 486
telemt_handshake_timeouts_total 488
telemt_upstream_connect_attempt_total 6241
telemt_upstream_connect_success_total 6064
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 6241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 4908
telemt_me_reader_eof_total 5162
telemt_me_idle_close_by_peer_total 5162
telemt_me_route_drop_no_conn_total 45531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4976
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4878
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 95174
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1846502668 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 60918368608 (56.73 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 22642.5 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345882
telemt_connections_bad_total 36828
telemt_connections_current 1611
telemt_connections_me_current 1611
telemt_handshake_timeouts_total 18204
telemt_upstream_connect_attempt_total 4780
telemt_upstream_connect_success_total 4780
telemt_upstream_connect_attempts_per_request{bucket="1"} 4780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3633
telemt_me_reconnect_success_total 3623
telemt_me_reader_eof_total 3818
telemt_me_idle_close_by_peer_total 3818
telemt_me_route_drop_no_conn_total 98114
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280453
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1427
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 886
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 559
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3662
telemt_me_writer_restored_same_endpoint_total 3608
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 280472
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 3029827888 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 156709359544 (145.95 GB)
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 202
```