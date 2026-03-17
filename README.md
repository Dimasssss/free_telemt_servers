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

# Server Metrics 2026-03-17 16:52:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 79614.3 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934672
telemt_connections_bad_total 6487
telemt_handshake_timeouts_total 26239
telemt_upstream_connect_attempt_total 18902
telemt_upstream_connect_success_total 18428
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 18902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29241
telemt_me_reconnect_success_total 12126
telemt_me_reader_eof_total 13238
telemt_me_idle_close_by_peer_total 13237
telemt_me_route_drop_no_conn_total 433376
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859314
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5770
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 4158
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 2237
telemt_desync_frames_bucket_total{bucket="gt_10"} 1912
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12828
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12104
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 853594
telemt_user_connections_current{user="hello"} 1251
telemt_user_octets_from_client{user="hello"} 13264518283 (12.35 GB)
telemt_user_octets_to_client{user="hello"} 285643481703 (266.03 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 79865.9 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697437
telemt_connections_bad_total 40545
telemt_handshake_timeouts_total 29443
telemt_upstream_connect_attempt_total 224061
telemt_upstream_connect_success_total 223404
telemt_upstream_connect_fail_total 648
telemt_upstream_connect_attempts_per_request{bucket="1"} 224052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 648
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 47076
telemt_me_reconnect_success_total 13559
telemt_me_reader_eof_total 15158
telemt_me_idle_close_by_peer_total 15158
telemt_me_route_drop_no_conn_total 207812
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1507
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1033
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14769
telemt_me_refill_failed_total 1043
telemt_me_writer_restored_same_endpoint_total 13543
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1210
telemt_user_connections_total{user="hello"} 595911
telemt_user_connections_current{user="hello"} 2653
telemt_user_octets_from_client{user="hello"} 7354656200 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 162725621077 (151.55 GB)
telemt_user_msgs_from_client{user="hello"} 3196293
telemt_user_msgs_to_client{user="hello"} 13192211
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 79642.1 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349541
telemt_connections_bad_total 9148
telemt_handshake_timeouts_total 20026
telemt_upstream_connect_attempt_total 20210
telemt_upstream_connect_success_total 20099
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 36710
telemt_me_reconnect_success_total 16044
telemt_me_reader_eof_total 17558
telemt_me_idle_close_by_peer_total 17555
telemt_me_route_drop_no_conn_total 179444
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304424
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 917
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 639
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16900
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16032
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 856
telemt_user_connections_total{user="hello"} 302597
telemt_user_connections_current{user="hello"} 1835
telemt_user_octets_from_client{user="hello"} 22075435248 (20.56 GB)
telemt_user_octets_to_client{user="hello"} 89919607784 (83.74 GB)
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 79701.1 (22h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783251
telemt_connections_bad_total 13500
telemt_handshake_timeouts_total 15374
telemt_upstream_connect_attempt_total 80000
telemt_upstream_connect_success_total 79608
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 80000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32519
telemt_me_reconnect_success_total 12225
telemt_me_reader_eof_total 13514
telemt_me_idle_close_by_peer_total 13513
telemt_me_route_drop_no_conn_total 289225
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618202
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2006
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1336
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 907
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13073
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12216
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 848
telemt_user_connections_total{user="hello"} 681334
telemt_user_connections_current{user="hello"} 2040
telemt_user_octets_from_client{user="hello"} 8474950099 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 211788622509 (197.24 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 79672.9 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383605
telemt_connections_bad_total 66686
telemt_handshake_timeouts_total 4078
telemt_upstream_connect_attempt_total 38266
telemt_upstream_connect_success_total 37769
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 38265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48563
telemt_me_reconnect_success_total 17270
telemt_me_reader_eof_total 18842
telemt_me_idle_close_by_peer_total 18840
telemt_me_route_drop_no_conn_total 108074
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279910
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1317
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18532
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17262
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1262
telemt_user_connections_total{user="hello"} 296619
telemt_user_connections_current{user="hello"} 1972
telemt_user_octets_from_client{user="hello"} 4189324004 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 120021250976 (111.78 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 79836.1 (22h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797869
telemt_connections_bad_total 60218
telemt_handshake_timeouts_total 7486
telemt_upstream_connect_attempt_total 16091
telemt_upstream_connect_success_total 16003
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 16091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23258
telemt_me_reconnect_success_total 11991
telemt_me_reader_eof_total 13059
telemt_me_idle_close_by_peer_total 13057
telemt_me_route_drop_no_conn_total 596553
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820969
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1352
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 530
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12541
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11977
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 689291
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 9987546608 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 306763563464 (285.70 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27601.3 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59752
telemt_connections_bad_total 2354
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 13962
telemt_upstream_connect_success_total 13845
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23854
telemt_me_reconnect_success_total 12280
telemt_me_reader_eof_total 13004
telemt_me_idle_close_by_peer_total 13004
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 17255
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53565
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12786
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12260
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 53562
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 3008588777 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 61987921606 (57.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 160
```