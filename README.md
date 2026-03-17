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

# Server Metrics 2026-03-17 20:16:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 91847.8 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138843
telemt_connections_bad_total 8386
telemt_handshake_timeouts_total 30356
telemt_upstream_connect_attempt_total 21058
telemt_upstream_connect_success_total 20570
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 21058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30804
telemt_me_reconnect_success_total 13675
telemt_me_reader_eof_total 14870
telemt_me_idle_close_by_peer_total 14869
telemt_me_route_drop_no_conn_total 510391
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043388
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6963
telemt_desync_full_logged_total 1993
telemt_desync_suppressed_total 4970
telemt_desync_frames_bucket_total{bucket="1_2"} 1875
telemt_desync_frames_bucket_total{bucket="3_10"} 2641
telemt_desync_frames_bucket_total{bucket="gt_10"} 2447
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14411
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13653
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 736
telemt_user_connections_total{user="hello"} 1037625
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 15730567875 (14.65 GB)
telemt_user_octets_to_client{user="hello"} 362753790715 (337.84 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 92099.0 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148819
telemt_connections_bad_total 58737
telemt_handshake_timeouts_total 41019
telemt_upstream_connect_attempt_total 456628
telemt_upstream_connect_success_total 455751
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 456628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57280
telemt_me_reconnect_success_total 14128
telemt_me_reader_eof_total 16068
telemt_me_idle_close_by_peer_total 16068
telemt_me_route_drop_no_conn_total 286963
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550959
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2340
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1583
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 990
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15652
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14112
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1524
telemt_user_connections_total{user="hello"} 987391
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 13703720566 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 314557099478 (292.95 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 91875.3 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626098
telemt_connections_bad_total 33341
telemt_handshake_timeouts_total 22248
telemt_upstream_connect_attempt_total 22243
telemt_upstream_connect_success_total 22114
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38126
telemt_me_reconnect_success_total 17453
telemt_me_reader_eof_total 19059
telemt_me_idle_close_by_peer_total 19052
telemt_me_route_drop_no_conn_total 271904
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1151
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18338
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17441
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 539238
telemt_user_connections_current{user="hello"} 1196
telemt_user_octets_from_client{user="hello"} 28081629640 (26.15 GB)
telemt_user_octets_to_client{user="hello"} 218522470148 (203.51 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 91934.7 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1126789
telemt_connections_bad_total 32111
telemt_handshake_timeouts_total 21012
telemt_upstream_connect_attempt_total 81826
telemt_upstream_connect_success_total 81418
telemt_upstream_connect_fail_total 408
telemt_upstream_connect_attempts_per_request{bucket="1"} 81826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 408
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33730
telemt_me_reconnect_success_total 13422
telemt_me_reader_eof_total 14802
telemt_me_idle_close_by_peer_total 14801
telemt_me_route_drop_no_conn_total 470115
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916433
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3110
telemt_desync_full_logged_total 992
telemt_desync_suppressed_total 2118
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 1334
telemt_desync_frames_bucket_total{bucket="gt_10"} 1022
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14306
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13413
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 979014
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 14307185327 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 389286629769 (362.55 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 91906.3 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679940
telemt_connections_bad_total 83064
telemt_handshake_timeouts_total 5647
telemt_upstream_connect_attempt_total 40486
telemt_upstream_connect_success_total 39946
telemt_upstream_connect_fail_total 540
telemt_upstream_connect_attempts_per_request{bucket="1"} 40486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 540
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51324
telemt_me_reconnect_success_total 18839
telemt_me_reader_eof_total 20542
telemt_me_idle_close_by_peer_total 20540
telemt_me_route_drop_no_conn_total 212362
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2422
telemt_desync_full_logged_total 679
telemt_desync_suppressed_total 1743
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20178
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18831
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1339
telemt_user_connections_total{user="hello"} 554248
telemt_user_connections_current{user="hello"} 1187
telemt_user_octets_from_client{user="hello"} 11018207564 (10.26 GB)
telemt_user_octets_to_client{user="hello"} 256859721776 (239.22 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 92067.5 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950136
telemt_connections_bad_total 68159
telemt_handshake_timeouts_total 9070
telemt_upstream_connect_attempt_total 18252
telemt_upstream_connect_success_total 18148
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24799
telemt_me_reconnect_success_total 13524
telemt_me_reader_eof_total 14698
telemt_me_idle_close_by_peer_total 14696
telemt_me_route_drop_no_conn_total 669417
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1898
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 77
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14101
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13510
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 817363
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 12591344372 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 353084316376 (328.84 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39834.6 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276127
telemt_connections_bad_total 36961
telemt_handshake_timeouts_total 7358
telemt_upstream_connect_attempt_total 16893
telemt_upstream_connect_success_total 16737
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26142
telemt_me_reconnect_success_total 14553
telemt_me_reader_eof_total 15381
telemt_me_idle_close_by_peer_total 15381
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 67330
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212217
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 635
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15089
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14525
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 212164
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 20002888033 (18.63 GB)
telemt_user_octets_to_client{user="hello"} 175326288406 (163.29 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 71
```