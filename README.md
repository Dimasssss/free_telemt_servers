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

# Server Metrics 2026-03-17 22:54:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 101345.4 (28h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219900
telemt_connections_bad_total 8801
telemt_handshake_timeouts_total 32230
telemt_upstream_connect_attempt_total 22865
telemt_upstream_connect_success_total 22370
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 22865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32148
telemt_me_reconnect_success_total 15016
telemt_me_reader_eof_total 16311
telemt_me_idle_close_by_peer_total 16310
telemt_me_route_drop_no_conn_total 542578
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1119744
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7380
telemt_desync_full_logged_total 2146
telemt_desync_suppressed_total 5234
telemt_desync_frames_bucket_total{bucket="1_2"} 1974
telemt_desync_frames_bucket_total{bucket="3_10"} 2789
telemt_desync_frames_bucket_total{bucket="gt_10"} 2617
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15770
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14994
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1113968
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 20808455487 (19.38 GB)
telemt_user_octets_to_client{user="hello"} 401865472939 (374.27 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 101596.8 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290996
telemt_connections_bad_total 60438
telemt_handshake_timeouts_total 45102
telemt_upstream_connect_attempt_total 458316
telemt_upstream_connect_success_total 457413
telemt_upstream_connect_fail_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 458316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 903
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58509
telemt_me_reconnect_success_total 15352
telemt_me_reader_eof_total 17369
telemt_me_idle_close_by_peer_total 17369
telemt_me_route_drop_no_conn_total 335487
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3113
telemt_desync_full_logged_total 1020
telemt_desync_suppressed_total 2093
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 1279
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16889
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15336
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1537
telemt_user_connections_total{user="hello"} 1119899
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 15441136586 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 383165919362 (356.85 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 101372.7 (28h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752628
telemt_connections_bad_total 46873
telemt_handshake_timeouts_total 23542
telemt_upstream_connect_attempt_total 23967
telemt_upstream_connect_success_total 23828
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39398
telemt_me_reconnect_success_total 18717
telemt_me_reader_eof_total 20406
telemt_me_idle_close_by_peer_total 20399
telemt_me_route_drop_no_conn_total 310274
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 700
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19620
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18705
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 640518
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 31204597396 (29.06 GB)
telemt_user_octets_to_client{user="hello"} 280896714716 (261.61 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 101432.2 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244628
telemt_connections_bad_total 44739
telemt_handshake_timeouts_total 21626
telemt_upstream_connect_attempt_total 83568
telemt_upstream_connect_success_total 83135
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 83568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35022
telemt_me_reconnect_success_total 14699
telemt_me_reader_eof_total 16198
telemt_me_idle_close_by_peer_total 16196
telemt_me_route_drop_no_conn_total 513195
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017692
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3822
telemt_desync_full_logged_total 1252
telemt_desync_suppressed_total 2570
telemt_desync_frames_bucket_total{bucket="1_2"} 938
telemt_desync_frames_bucket_total{bucket="3_10"} 1606
telemt_desync_frames_bucket_total{bucket="gt_10"} 1278
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15606
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14690
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 907
telemt_user_connections_total{user="hello"} 1080181
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 16917130603 (15.76 GB)
telemt_user_octets_to_client{user="hello"} 482739068121 (449.59 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 101404.0 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802354
telemt_connections_bad_total 95130
telemt_handshake_timeouts_total 6444
telemt_upstream_connect_attempt_total 42579
telemt_upstream_connect_success_total 42002
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 42579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 403
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55406
telemt_me_reconnect_success_total 20453
telemt_me_reader_eof_total 22285
telemt_me_idle_close_by_peer_total 22283
telemt_me_route_drop_no_conn_total 254533
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643346
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2965
telemt_desync_full_logged_total 872
telemt_desync_suppressed_total 2093
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21891
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20445
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1438
telemt_user_connections_total{user="hello"} 659958
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 12617392056 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 328178156476 (305.64 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 101565.0 (28h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033102
telemt_connections_bad_total 87342
telemt_handshake_timeouts_total 9524
telemt_upstream_connect_attempt_total 20063
telemt_upstream_connect_success_total 19949
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26170
telemt_me_reconnect_success_total 14890
telemt_me_reader_eof_total 16164
telemt_me_idle_close_by_peer_total 16162
telemt_me_route_drop_no_conn_total 695746
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008234
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2091
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1360
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 836
telemt_pool_swap_total 87
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15488
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14876
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 871260
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 13434132236 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 369976638260 (344.57 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 49332.2 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364475
telemt_connections_bad_total 44509
telemt_handshake_timeouts_total 10614
telemt_upstream_connect_attempt_total 18959
telemt_upstream_connect_success_total 18783
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 18959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27757
telemt_me_reconnect_success_total 16162
telemt_me_reader_eof_total 17085
telemt_me_idle_close_by_peer_total 17085
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 91154
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275199
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 977
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 673
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16712
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16133
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 275137
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 21378266765 (19.91 GB)
telemt_user_octets_to_client{user="hello"} 226243906294 (210.71 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 30
```