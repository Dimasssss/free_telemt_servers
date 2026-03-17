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

# Server Metrics 2026-03-17 22:18:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 99200.1 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205613
telemt_connections_bad_total 8710
telemt_handshake_timeouts_total 31620
telemt_upstream_connect_attempt_total 22470
telemt_upstream_connect_success_total 21976
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31840
telemt_me_reconnect_success_total 14708
telemt_me_reader_eof_total 15987
telemt_me_idle_close_by_peer_total 15986
telemt_me_route_drop_no_conn_total 537015
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1106431
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7313
telemt_desync_full_logged_total 2116
telemt_desync_suppressed_total 5197
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 2761
telemt_desync_frames_bucket_total{bucket="gt_10"} 2597
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15460
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14686
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 1100663
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 20089159371 (18.71 GB)
telemt_user_octets_to_client{user="hello"} 393672443783 (366.64 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 99451.7 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1272243
telemt_connections_bad_total 60251
telemt_handshake_timeouts_total 44868
telemt_upstream_connect_attempt_total 457898
telemt_upstream_connect_success_total 456998
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 457898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58181
telemt_me_reconnect_success_total 15025
telemt_me_reader_eof_total 17022
telemt_me_idle_close_by_peer_total 17022
telemt_me_route_drop_no_conn_total 328058
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2977
telemt_desync_full_logged_total 966
telemt_desync_suppressed_total 2011
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1220
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 16560
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15009
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1101801
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 15168316958 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 371882372498 (346.34 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 99227.7 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730886
telemt_connections_bad_total 45059
telemt_handshake_timeouts_total 23086
telemt_upstream_connect_attempt_total 23544
telemt_upstream_connect_success_total 23405
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39063
telemt_me_reconnect_success_total 18385
telemt_me_reader_eof_total 20053
telemt_me_idle_close_by_peer_total 20046
telemt_me_route_drop_no_conn_total 304166
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627228
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2057
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1419
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19281
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18373
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 625492
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 30888206072 (28.77 GB)
telemt_user_octets_to_client{user="hello"} 272301704528 (253.60 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 99287.3 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227094
telemt_connections_bad_total 42314
telemt_handshake_timeouts_total 21568
telemt_upstream_connect_attempt_total 83181
telemt_upstream_connect_success_total 82750
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 83181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34723
telemt_me_reconnect_success_total 14401
telemt_me_reader_eof_total 15880
telemt_me_idle_close_by_peer_total 15878
telemt_me_route_drop_no_conn_total 507291
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002964
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3666
telemt_desync_full_logged_total 1197
telemt_desync_suppressed_total 2469
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 1535
telemt_desync_frames_bucket_total{bucket="gt_10"} 1232
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15303
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14392
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1065461
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 16719275867 (15.57 GB)
telemt_user_octets_to_client{user="hello"} 467286710205 (435.19 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 99259.1 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784160
telemt_connections_bad_total 93417
telemt_handshake_timeouts_total 6414
telemt_upstream_connect_attempt_total 42129
telemt_upstream_connect_success_total 41559
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 42129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55049
telemt_me_reconnect_success_total 20098
telemt_me_reader_eof_total 21919
telemt_me_idle_close_by_peer_total 21917
telemt_me_route_drop_no_conn_total 247924
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627386
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2858
telemt_desync_full_logged_total 844
telemt_desync_suppressed_total 2014
telemt_desync_frames_bucket_total{bucket="1_2"} 912
telemt_desync_frames_bucket_total{bucket="3_10"} 1149
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21530
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20090
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1432
telemt_user_connections_total{user="hello"} 643996
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 12446595604 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 318668172428 (296.78 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 99420.0 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017566
telemt_connections_bad_total 81603
telemt_handshake_timeouts_total 9493
telemt_upstream_connect_attempt_total 19657
telemt_upstream_connect_success_total 19544
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25851
telemt_me_reconnect_success_total 14573
telemt_me_reader_eof_total 15827
telemt_me_idle_close_by_peer_total 15825
telemt_me_route_drop_no_conn_total 691361
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999822
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
telemt_pool_swap_total 85
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15165
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14559
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 862851
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 13361771476 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 367491123048 (342.25 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 47187.4 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353135
telemt_connections_bad_total 44370
telemt_handshake_timeouts_total 10549
telemt_upstream_connect_attempt_total 18423
telemt_upstream_connect_success_total 18249
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 18423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27309
telemt_me_reconnect_success_total 15715
telemt_me_reader_eof_total 16611
telemt_me_idle_close_by_peer_total 16611
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 87683
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267949
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 630
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16261
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15686
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 267889
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 21274484605 (19.81 GB)
telemt_user_octets_to_client{user="hello"} 220992495870 (205.82 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 41
```