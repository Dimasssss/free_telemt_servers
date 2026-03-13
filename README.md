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

# Server Metrics 2026-03-13 15:15:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 114112.8 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474056
telemt_connections_bad_total 3230
telemt_handshake_timeouts_total 8656
telemt_upstream_connect_attempt_total 28605
telemt_upstream_connect_success_total 28468
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2475
telemt_me_reconnect_attempts_total 26301
telemt_me_reconnect_success_total 22768
telemt_me_reader_eof_total 24323
telemt_me_idle_close_by_peer_total 24322
telemt_me_route_drop_no_conn_total 154647
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23117
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22752
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 415579
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 7468958984 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 193877752032 (180.56 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 114006.8 (31h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226214
telemt_connections_bad_total 1833
telemt_handshake_timeouts_total 1583
telemt_upstream_connect_attempt_total 83713
telemt_upstream_connect_success_total 82942
telemt_upstream_connect_fail_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 83713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 771
telemt_me_keepalive_timeout_total 1404
telemt_me_reconnect_attempts_total 112178
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29473
telemt_me_idle_close_by_peer_total 29473
telemt_me_route_drop_no_conn_total 81089
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162870
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28938
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2916
telemt_user_connections_total{user="hello"} 213885
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2166145747 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 67718595022 (63.07 GB)
telemt_user_msgs_from_client{user="hello"} 762156
telemt_user_msgs_to_client{user="hello"} 4975118
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 113969.9 (31h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273513
telemt_connections_bad_total 2428
telemt_handshake_timeouts_total 12411
telemt_upstream_connect_attempt_total 30636
telemt_upstream_connect_success_total 30632
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2329
telemt_me_reconnect_attempts_total 26110
telemt_me_reconnect_success_total 24890
telemt_me_reader_eof_total 26673
telemt_me_idle_close_by_peer_total 26673
telemt_me_route_drop_no_conn_total 98684
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248924
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 25164
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24870
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 248839
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9567200644 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 106325760560 (99.02 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 113945.5 (31h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372976
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3690
telemt_upstream_connect_attempt_total 42649
telemt_upstream_connect_success_total 32492
telemt_upstream_connect_fail_total 10157
telemt_upstream_connect_attempts_per_request{bucket="1"} 42649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10157
telemt_me_keepalive_timeout_total 4162
telemt_me_reconnect_attempts_total 101132
telemt_me_reconnect_success_total 23750
telemt_me_reader_eof_total 26874
telemt_me_idle_close_by_peer_total 26867
telemt_me_route_drop_no_conn_total 133821
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322981
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1264
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 886
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26473
telemt_me_refill_failed_total 2413
telemt_me_writer_restored_same_endpoint_total 23740
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2723
telemt_user_connections_total{user="hello"} 325891
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 6895979034 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 123128299409 (114.67 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64117.0 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99432
telemt_connections_bad_total 12849
telemt_handshake_timeouts_total 1236
telemt_upstream_connect_attempt_total 26229
telemt_upstream_connect_success_total 26003
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 26229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 29042
telemt_me_reconnect_success_total 17870
telemt_me_reader_eof_total 19170
telemt_me_idle_close_by_peer_total 19170
telemt_me_route_drop_no_conn_total 30029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 18374
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 17852
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 82153
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 946854233 (902.99 MB)
telemt_user_octets_to_client{user="hello"} 24950724443 (23.24 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 113902.5 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682036
telemt_connections_bad_total 20707
telemt_handshake_timeouts_total 21683
telemt_upstream_connect_attempt_total 23933
telemt_upstream_connect_success_total 23812
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 23933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2551
telemt_me_reconnect_attempts_total 22777
telemt_me_reconnect_success_total 18150
telemt_me_reader_eof_total 19481
telemt_me_idle_close_by_peer_total 19478
telemt_me_route_drop_no_conn_total 325388
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644097
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18529
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18143
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 617050
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 10543751832 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 321454281872 (299.38 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 86
```