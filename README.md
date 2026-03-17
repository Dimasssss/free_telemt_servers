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

# Server Metrics 2026-03-17 18:39:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 86040.1 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1050181
telemt_connections_bad_total 7481
telemt_handshake_timeouts_total 28387
telemt_upstream_connect_attempt_total 20044
telemt_upstream_connect_success_total 19562
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 20044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 30073
telemt_me_reconnect_success_total 12952
telemt_me_reader_eof_total 14105
telemt_me_idle_close_by_peer_total 14104
telemt_me_route_drop_no_conn_total 477866
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 961385
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6324
telemt_desync_full_logged_total 1803
telemt_desync_suppressed_total 4521
telemt_desync_frames_bucket_total{bucket="1_2"} 1739
telemt_desync_frames_bucket_total{bucket="3_10"} 2430
telemt_desync_frames_bucket_total{bucket="gt_10"} 2155
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13673
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12930
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 955625
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 14527183627 (13.53 GB)
telemt_user_octets_to_client{user="hello"} 333622301043 (310.71 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 86291.8 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004563
telemt_connections_bad_total 55825
telemt_handshake_timeouts_total 34145
telemt_upstream_connect_attempt_total 450223
telemt_upstream_connect_success_total 449360
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 450223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 376673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43270
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56714
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15464
telemt_me_idle_close_by_peer_total 15464
telemt_me_route_drop_no_conn_total 243036
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429277
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1077
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15076
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1511
telemt_user_connections_total{user="hello"} 860656
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 11567307278 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 225626659737 (210.13 GB)
telemt_user_msgs_from_client{user="hello"} 7292782
telemt_user_msgs_to_client{user="hello"} 31023705
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 86067.9 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516136
telemt_connections_bad_total 19017
telemt_handshake_timeouts_total 21242
telemt_upstream_connect_attempt_total 21233
telemt_upstream_connect_success_total 21115
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37420
telemt_me_reconnect_success_total 16751
telemt_me_reader_eof_total 18316
telemt_me_idle_close_by_peer_total 18309
telemt_me_route_drop_no_conn_total 235336
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450636
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1247
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 17622
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16739
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 448835
telemt_user_connections_current{user="hello"} 1125
telemt_user_octets_from_client{user="hello"} 26644261748 (24.81 GB)
telemt_user_octets_to_client{user="hello"} 166589478992 (155.15 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 86127.2 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000359
telemt_connections_bad_total 24583
telemt_handshake_timeouts_total 19492
telemt_upstream_connect_attempt_total 80930
telemt_upstream_connect_success_total 80528
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 80930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33141
telemt_me_reconnect_success_total 12839
telemt_me_reader_eof_total 14175
telemt_me_idle_close_by_peer_total 14174
telemt_me_route_drop_no_conn_total 418723
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806639
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2581
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1137
telemt_desync_frames_bucket_total{bucket="gt_10"} 823
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13709
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12830
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 869710
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 11210343735 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 314484676337 (292.89 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 86099.3 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571723
telemt_connections_bad_total 75471
telemt_handshake_timeouts_total 5075
telemt_upstream_connect_attempt_total 39521
telemt_upstream_connect_success_total 38999
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 39521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50671
telemt_me_reconnect_success_total 18190
telemt_me_reader_eof_total 19839
telemt_me_idle_close_by_peer_total 19837
telemt_me_route_drop_no_conn_total 172446
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441727
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1969
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 1459
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19513
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18182
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 458397
telemt_user_connections_current{user="hello"} 1375
telemt_user_octets_from_client{user="hello"} 8298388216 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 211030473592 (196.54 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 86260.7 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882184
telemt_connections_bad_total 61431
telemt_handshake_timeouts_total 8586
telemt_upstream_connect_attempt_total 17219
telemt_upstream_connect_success_total 17123
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24077
telemt_me_reconnect_success_total 12804
telemt_me_reader_eof_total 13928
telemt_me_idle_close_by_peer_total 13926
telemt_me_route_drop_no_conn_total 643022
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 900198
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1713
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 644
telemt_pool_swap_total 70
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13374
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12790
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 763248
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 11645806176 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 330614979140 (307.91 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34027.1 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193820
telemt_connections_bad_total 20646
telemt_handshake_timeouts_total 5656
telemt_upstream_connect_attempt_total 15243
telemt_upstream_connect_success_total 15111
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 15243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24818
telemt_me_reconnect_success_total 13238
telemt_me_reader_eof_total 14012
telemt_me_idle_close_by_peer_total 14012
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 47093
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154385
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 360
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 13755
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13214
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 154333
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 13005485185 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 138478017350 (128.97 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 98
```