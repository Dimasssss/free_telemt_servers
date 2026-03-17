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

# Server Metrics 2026-03-17 22:28:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 99812.4 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209733
telemt_connections_bad_total 8746
telemt_handshake_timeouts_total 31696
telemt_upstream_connect_attempt_total 22555
telemt_upstream_connect_success_total 22061
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31925
telemt_me_reconnect_success_total 14793
telemt_me_reader_eof_total 16072
telemt_me_idle_close_by_peer_total 16071
telemt_me_route_drop_no_conn_total 538801
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110385
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7318
telemt_desync_full_logged_total 2120
telemt_desync_suppressed_total 5198
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 2764
telemt_desync_frames_bucket_total{bucket="gt_10"} 2599
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15545
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14771
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 1104610
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 20131145371 (18.75 GB)
telemt_user_octets_to_client{user="hello"} 396988227671 (369.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 100064.1 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277541
telemt_connections_bad_total 60307
telemt_handshake_timeouts_total 44940
telemt_upstream_connect_attempt_total 458020
telemt_upstream_connect_success_total 457118
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 458020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58257
telemt_me_reconnect_success_total 15101
telemt_me_reader_eof_total 17101
telemt_me_idle_close_by_peer_total 17101
telemt_me_route_drop_no_conn_total 330662
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670467
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2987
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1225
telemt_desync_frames_bucket_total{bucket="gt_10"} 1194
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16636
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15085
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1106902
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 15213054002 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 375677145306 (349.88 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 99839.9 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738136
telemt_connections_bad_total 45532
telemt_handshake_timeouts_total 23479
telemt_upstream_connect_attempt_total 23625
telemt_upstream_connect_success_total 23486
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39144
telemt_me_reconnect_success_total 18465
telemt_me_reader_eof_total 20135
telemt_me_idle_close_by_peer_total 20128
telemt_me_route_drop_no_conn_total 306011
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632284
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2083
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19363
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18453
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 898
telemt_user_connections_total{user="hello"} 630548
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 30918817356 (28.80 GB)
telemt_user_octets_to_client{user="hello"} 273926163828 (255.11 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 99899.5 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232427
telemt_connections_bad_total 43265
telemt_handshake_timeouts_total 21576
telemt_upstream_connect_attempt_total 83255
telemt_upstream_connect_success_total 82824
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 83255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34797
telemt_me_reconnect_success_total 14475
telemt_me_reader_eof_total 15954
telemt_me_idle_close_by_peer_total 15952
telemt_me_route_drop_no_conn_total 508753
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007232
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3713
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 2500
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1246
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15377
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14466
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1069724
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 16762134139 (15.61 GB)
telemt_user_octets_to_client{user="hello"} 471095132797 (438.74 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 99871.3 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790684
telemt_connections_bad_total 94831
telemt_handshake_timeouts_total 6420
telemt_upstream_connect_attempt_total 42184
telemt_upstream_connect_success_total 41614
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 42184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55104
telemt_me_reconnect_success_total 20152
telemt_me_reader_eof_total 21974
telemt_me_idle_close_by_peer_total 21972
telemt_me_route_drop_no_conn_total 250105
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632350
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2881
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 2029
telemt_desync_frames_bucket_total{bucket="1_2"} 924
telemt_desync_frames_bucket_total{bucket="3_10"} 1157
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21585
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20144
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1433
telemt_user_connections_total{user="hello"} 648960
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 12482133376 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 320706248048 (298.68 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 100032.1 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021951
telemt_connections_bad_total 83236
telemt_handshake_timeouts_total 9510
telemt_upstream_connect_attempt_total 19783
telemt_upstream_connect_success_total 19670
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25934
telemt_me_reconnect_success_total 14655
telemt_me_reader_eof_total 15913
telemt_me_idle_close_by_peer_total 15911
telemt_me_route_drop_no_conn_total 692327
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002168
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 834
telemt_pool_swap_total 86
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15250
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14641
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 595
telemt_user_connections_total{user="hello"} 865197
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 13377145692 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 368082919756 (342.80 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 47799.5 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356819
telemt_connections_bad_total 44418
telemt_handshake_timeouts_total 10554
telemt_upstream_connect_attempt_total 18554
telemt_upstream_connect_success_total 18379
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 18554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27398
telemt_me_reconnect_success_total 15803
telemt_me_reader_eof_total 16700
telemt_me_idle_close_by_peer_total 16700
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 89004
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270380
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16350
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15774
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 270318
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 21306514625 (19.84 GB)
telemt_user_octets_to_client{user="hello"} 222474228038 (207.20 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 36
```