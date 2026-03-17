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

# Server Metrics 2026-03-17 19:04:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 87568.1 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074882
telemt_connections_bad_total 7596
telemt_handshake_timeouts_total 29825
telemt_upstream_connect_attempt_total 20391
telemt_upstream_connect_success_total 19904
telemt_upstream_connect_fail_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 20391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 30329
telemt_me_reconnect_success_total 13203
telemt_me_reader_eof_total 14369
telemt_me_idle_close_by_peer_total 14368
telemt_me_route_drop_no_conn_total 486766
telemt_me_route_drop_channel_closed_total 140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983663
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6427
telemt_desync_full_logged_total 1843
telemt_desync_suppressed_total 4584
telemt_desync_frames_bucket_total{bucket="1_2"} 1762
telemt_desync_frames_bucket_total{bucket="3_10"} 2460
telemt_desync_frames_bucket_total{bucket="gt_10"} 2205
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13931
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13181
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 977901
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 14916565231 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 341957289119 (318.47 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 87819.8 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1047155
telemt_connections_bad_total 55870
telemt_handshake_timeouts_total 35602
telemt_upstream_connect_attempt_total 455987
telemt_upstream_connect_success_total 455118
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 455987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56863
telemt_me_reconnect_success_total 13714
telemt_me_reader_eof_total 15619
telemt_me_idle_close_by_peer_total 15619
telemt_me_route_drop_no_conn_total 255013
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461979
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 15226
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13698
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 898466
telemt_user_connections_current{user="hello"} 1638
telemt_user_octets_from_client{user="hello"} 12335124874 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 249045643650 (231.94 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 87595.9 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542960
telemt_connections_bad_total 19120
telemt_handshake_timeouts_total 21658
telemt_upstream_connect_attempt_total 21499
telemt_upstream_connect_success_total 21377
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37596
telemt_me_reconnect_success_total 16926
telemt_me_reader_eof_total 18506
telemt_me_idle_close_by_peer_total 18499
telemt_me_route_drop_no_conn_total 244880
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475464
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1303
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 914
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 17800
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16914
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 874
telemt_user_connections_total{user="hello"} 473650
telemt_user_connections_current{user="hello"} 1088
telemt_user_octets_from_client{user="hello"} 26969258884 (25.12 GB)
telemt_user_octets_to_client{user="hello"} 180182863156 (167.81 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 87655.0 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035359
telemt_connections_bad_total 24999
telemt_handshake_timeouts_total 19940
telemt_upstream_connect_attempt_total 81172
telemt_upstream_connect_success_total 80769
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 81172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33295
telemt_me_reconnect_success_total 12993
telemt_me_reader_eof_total 14339
telemt_me_idle_close_by_peer_total 14338
telemt_me_route_drop_no_conn_total 431030
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836353
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2713
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 1833
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 1179
telemt_desync_frames_bucket_total{bucket="gt_10"} 886
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13864
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12984
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 899419
telemt_user_connections_current{user="hello"} 1439
telemt_user_octets_from_client{user="hello"} 12746830867 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 333309311225 (310.42 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 87626.9 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598399
telemt_connections_bad_total 75750
telemt_handshake_timeouts_total 5109
telemt_upstream_connect_attempt_total 39793
telemt_upstream_connect_success_total 39266
telemt_upstream_connect_fail_total 527
telemt_upstream_connect_attempts_per_request{bucket="1"} 39793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 527
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50852
telemt_me_reconnect_success_total 18370
telemt_me_reader_eof_total 20035
telemt_me_idle_close_by_peer_total 20033
telemt_me_route_drop_no_conn_total 182913
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2122
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1565
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19698
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18362
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1328
telemt_user_connections_total{user="hello"} 483791
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 8703316324 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 224320768080 (208.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 87788.3 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897733
telemt_connections_bad_total 61457
telemt_handshake_timeouts_total 8866
telemt_upstream_connect_attempt_total 17495
telemt_upstream_connect_success_total 17396
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24263
telemt_me_reconnect_success_total 12990
telemt_me_reader_eof_total 14126
telemt_me_idle_close_by_peer_total 14124
telemt_me_route_drop_no_conn_total 649907
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 914347
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1770
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 1160
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
telemt_pool_swap_total 72
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13562
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12976
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 777393
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 11886351412 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 336302258388 (313.21 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35555.1 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221078
telemt_connections_bad_total 25896
telemt_handshake_timeouts_total 6002
telemt_upstream_connect_attempt_total 15606
telemt_upstream_connect_success_total 15471
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25091
telemt_me_reconnect_success_total 13508
telemt_me_reader_eof_total 14293
telemt_me_idle_close_by_peer_total 14293
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 53073
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172458
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14030
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13484
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 172398
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 16052273677 (14.95 GB)
telemt_user_octets_to_client{user="hello"} 150196860590 (139.88 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 95
```