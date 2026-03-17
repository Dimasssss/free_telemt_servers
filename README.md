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

# Server Metrics 2026-03-17 15:35:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 75023.4 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830114
telemt_connections_bad_total 6212
telemt_handshake_timeouts_total 24180
telemt_upstream_connect_attempt_total 17874
telemt_upstream_connect_success_total 17403
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 17874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26035
telemt_me_reconnect_success_total 11326
telemt_me_reader_eof_total 12335
telemt_me_idle_close_by_peer_total 12334
telemt_me_route_drop_no_conn_total 348541
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754537
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5231
telemt_desync_full_logged_total 1452
telemt_desync_suppressed_total 3779
telemt_desync_frames_bucket_total{bucket="1_2"} 1506
telemt_desync_frames_bucket_total{bucket="3_10"} 2064
telemt_desync_frames_bucket_total{bucket="gt_10"} 1661
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11939
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11304
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 756369
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 12097163723 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 249757093655 (232.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 75275.3 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546479
telemt_connections_bad_total 31851
telemt_handshake_timeouts_total 28368
telemt_upstream_connect_attempt_total 108460
telemt_upstream_connect_success_total 107910
telemt_upstream_connect_fail_total 545
telemt_upstream_connect_attempts_per_request{bucket="1"} 108455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7922
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 545
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 40111
telemt_me_reconnect_success_total 13476
telemt_me_reader_eof_total 14862
telemt_me_idle_close_by_peer_total 14862
telemt_me_route_drop_no_conn_total 194183
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14471
telemt_me_refill_failed_total 828
telemt_me_writer_restored_same_endpoint_total 13460
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 995
telemt_user_connections_total{user="hello"} 461150
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 5124093340 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 131891412644 (122.83 GB)
telemt_user_msgs_from_client{user="hello"} 1318785
telemt_user_msgs_to_client{user="hello"} 4688842
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 75051.0 (20h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279035
telemt_connections_bad_total 7840
telemt_handshake_timeouts_total 18620
telemt_upstream_connect_attempt_total 19567
telemt_upstream_connect_success_total 19464
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 30773
telemt_me_reconnect_success_total 15639
telemt_me_reader_eof_total 16976
telemt_me_idle_close_by_peer_total 16973
telemt_me_route_drop_no_conn_total 131388
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16321
telemt_me_refill_failed_total 470
telemt_me_writer_restored_same_endpoint_total 15628
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 238210
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 18389084428 (17.13 GB)
telemt_user_octets_to_client{user="hello"} 58265152796 (54.26 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 75110.4 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650303
telemt_connections_bad_total 8775
telemt_handshake_timeouts_total 13847
telemt_upstream_connect_attempt_total 36134
telemt_upstream_connect_success_total 35905
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 36134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 29493
telemt_me_reconnect_success_total 11958
telemt_me_reader_eof_total 13155
telemt_me_idle_close_by_peer_total 13154
telemt_me_route_drop_no_conn_total 253838
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541741
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12714
telemt_me_refill_failed_total 543
telemt_me_writer_restored_same_endpoint_total 11949
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 756
telemt_user_connections_total{user="hello"} 561681
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 6801743519 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 170820425483 (159.09 GB)
telemt_user_msgs_from_client{user="hello"} 184846
telemt_user_msgs_to_client{user="hello"} 909343
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 75082.3 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298557
telemt_connections_bad_total 57642
telemt_handshake_timeouts_total 3714
telemt_upstream_connect_attempt_total 21531
telemt_upstream_connect_success_total 21056
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 21531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 44097
telemt_me_reconnect_success_total 16873
telemt_me_reader_eof_total 18313
telemt_me_idle_close_by_peer_total 18311
telemt_me_route_drop_no_conn_total 84920
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18003
telemt_me_refill_failed_total 846
telemt_me_writer_restored_same_endpoint_total 16865
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1130
telemt_user_connections_total{user="hello"} 225178
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 2784179775 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 83818863743 (78.06 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 75244.0 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727323
telemt_connections_bad_total 59214
telemt_handshake_timeouts_total 7069
telemt_upstream_connect_attempt_total 15179
telemt_upstream_connect_success_total 15097
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21610
telemt_me_reconnect_success_total 11313
telemt_me_reader_eof_total 12305
telemt_me_idle_close_by_peer_total 12305
telemt_me_route_drop_no_conn_total 532135
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738298
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1090
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11812
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11299
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 624379
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 9183007840 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 278808531620 (259.66 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23010.4 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17839
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 12387
telemt_upstream_connect_success_total 12281
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 22506
telemt_me_reconnect_success_total 10941
telemt_me_reader_eof_total 11586
telemt_me_idle_close_by_peer_total 11586
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 6670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16983
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11422
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10925
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 17080
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 545500077 (520.23 MB)
telemt_user_octets_to_client{user="hello"} 24026186998 (22.38 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```