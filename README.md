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

# Server Metrics 2026-03-18 03:03:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 116312.8 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334746
telemt_connections_bad_total 10365
telemt_handshake_timeouts_total 33285
telemt_upstream_connect_attempt_total 25794
telemt_upstream_connect_success_total 25285
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34328
telemt_me_reconnect_success_total 17187
telemt_me_reader_eof_total 18654
telemt_me_idle_close_by_peer_total 18653
telemt_me_route_drop_no_conn_total 575085
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1228757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7820
telemt_desync_full_logged_total 2324
telemt_desync_suppressed_total 5496
telemt_desync_frames_bucket_total{bucket="1_2"} 2077
telemt_desync_frames_bucket_total{bucket="3_10"} 2988
telemt_desync_frames_bucket_total{bucket="gt_10"} 2755
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17977
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17165
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 790
telemt_user_connections_total{user="hello"} 1222972
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 24758684907 (23.06 GB)
telemt_user_octets_to_client{user="hello"} 433471095211 (403.70 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 116564.3 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1410914
telemt_connections_bad_total 64570
telemt_handshake_timeouts_total 47472
telemt_upstream_connect_attempt_total 468927
telemt_upstream_connect_success_total 467337
telemt_upstream_connect_fail_total 1590
telemt_upstream_connect_attempts_per_request{bucket="1"} 468927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1590
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125327
telemt_me_reconnect_success_total 18605
telemt_me_reader_eof_total 20824
telemt_me_idle_close_by_peer_total 20811
telemt_me_route_drop_no_conn_total 363716
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785606
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3657
telemt_desync_full_logged_total 1259
telemt_desync_suppressed_total 2398
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 1527
telemt_desync_frames_bucket_total{bucket="gt_10"} 1409
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 20217
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18587
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1612
telemt_user_connections_total{user="hello"} 1227951
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 16498265809 (15.37 GB)
telemt_user_octets_to_client{user="hello"} 433221075050 (403.47 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 116340.2 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858528
telemt_connections_bad_total 60751
telemt_handshake_timeouts_total 24784
telemt_upstream_connect_attempt_total 27110
telemt_upstream_connect_success_total 26954
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 27110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41796
telemt_me_reconnect_success_total 21101
telemt_me_reader_eof_total 22955
telemt_me_idle_close_by_peer_total 22948
telemt_me_route_drop_no_conn_total 336478
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721449
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2269
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1533
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 22030
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21089
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 719565
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 44186771176 (41.15 GB)
telemt_user_octets_to_client{user="hello"} 321594864648 (299.51 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 116399.7 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1335234
telemt_connections_bad_total 61483
telemt_handshake_timeouts_total 22916
telemt_upstream_connect_attempt_total 89979
telemt_upstream_connect_success_total 87556
telemt_upstream_connect_fail_total 2423
telemt_upstream_connect_attempts_per_request{bucket="1"} 89979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2423
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37385
telemt_me_reconnect_success_total 16981
telemt_me_reader_eof_total 18683
telemt_me_idle_close_by_peer_total 18680
telemt_me_route_drop_no_conn_total 546533
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1084253
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4019
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2689
telemt_desync_frames_bucket_total{bucket="1_2"} 988
telemt_desync_frames_bucket_total{bucket="3_10"} 1678
telemt_desync_frames_bucket_total{bucket="gt_10"} 1353
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17936
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16961
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 955
telemt_user_connections_total{user="hello"} 1147620
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 17906561038 (16.68 GB)
telemt_user_octets_to_client{user="hello"} 544558349886 (507.16 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 116371.6 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894268
telemt_connections_bad_total 101250
telemt_handshake_timeouts_total 7001
telemt_upstream_connect_attempt_total 46806
telemt_upstream_connect_success_total 46168
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 58839
telemt_me_reconnect_success_total 23875
telemt_me_reader_eof_total 25872
telemt_me_idle_close_by_peer_total 25869
telemt_me_route_drop_no_conn_total 285899
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723891
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3308
telemt_desync_full_logged_total 996
telemt_desync_suppressed_total 2312
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1321
telemt_desync_frames_bucket_total{bucket="gt_10"} 958
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25344
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23867
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1469
telemt_user_connections_total{user="hello"} 740409
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 14066244304 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 365156821880 (340.08 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 116532.5 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141715
telemt_connections_bad_total 126836
telemt_handshake_timeouts_total 10123
telemt_upstream_connect_attempt_total 23216
telemt_upstream_connect_success_total 23082
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 23216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28569
telemt_me_reconnect_success_total 17279
telemt_me_reader_eof_total 18735
telemt_me_idle_close_by_peer_total 18733
telemt_me_route_drop_no_conn_total 786697
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1115420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 104
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17901
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17265
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 933499
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 14998551004 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 409855081644 (381.71 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 64299.8 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442208
telemt_connections_bad_total 44846
telemt_handshake_timeouts_total 11765
telemt_upstream_connect_attempt_total 23488
telemt_upstream_connect_success_total 23256
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 23488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31501
telemt_me_reconnect_success_total 19892
telemt_me_reader_eof_total 21034
telemt_me_idle_close_by_peer_total 21034
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 109121
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320585
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1392
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 942
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20472
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19852
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 320379
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 22740065781 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 269207454554 (250.72 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 44
```