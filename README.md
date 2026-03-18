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

# Server Metrics 2026-03-18 04:55:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 123033.5 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1410519
telemt_connections_bad_total 10543
telemt_handshake_timeouts_total 34477
telemt_upstream_connect_attempt_total 26954
telemt_upstream_connect_success_total 26440
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 26954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35182
telemt_me_reconnect_success_total 18034
telemt_me_reader_eof_total 19560
telemt_me_idle_close_by_peer_total 19559
telemt_me_route_drop_no_conn_total 599507
telemt_me_route_drop_channel_closed_total 165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294776
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8021
telemt_desync_full_logged_total 2399
telemt_desync_suppressed_total 5622
telemt_desync_frames_bucket_total{bucket="1_2"} 2109
telemt_desync_frames_bucket_total{bucket="3_10"} 3075
telemt_desync_frames_bucket_total{bucket="gt_10"} 2837
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18836
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18012
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 802
telemt_user_connections_total{user="hello"} 1289011
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 29708048199 (27.67 GB)
telemt_user_octets_to_client{user="hello"} 456190494055 (424.86 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 123284.8 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1529390
telemt_connections_bad_total 73995
telemt_handshake_timeouts_total 50513
telemt_upstream_connect_attempt_total 470370
telemt_upstream_connect_success_total 468747
telemt_upstream_connect_fail_total 1623
telemt_upstream_connect_attempts_per_request{bucket="1"} 470370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1623
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126436
telemt_me_reconnect_success_total 19708
telemt_me_reader_eof_total 21979
telemt_me_idle_close_by_peer_total 21966
telemt_me_route_drop_no_conn_total 398562
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 888592
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3976
telemt_desync_full_logged_total 1386
telemt_desync_suppressed_total 2590
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1625
telemt_desync_frames_bucket_total{bucket="gt_10"} 1569
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 21329
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19690
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1621
telemt_user_connections_total{user="hello"} 1330904
telemt_user_connections_current{user="hello"} 1280
telemt_user_octets_from_client{user="hello"} 17999971033 (16.76 GB)
telemt_user_octets_to_client{user="hello"} 496401802458 (462.31 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 123060.8 (34h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968686
telemt_connections_bad_total 68612
telemt_handshake_timeouts_total 27770
telemt_upstream_connect_attempt_total 28324
telemt_upstream_connect_success_total 28163
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42702
telemt_me_reconnect_success_total 22002
telemt_me_reader_eof_total 23915
telemt_me_idle_close_by_peer_total 23908
telemt_me_route_drop_no_conn_total 362347
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2574
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1725
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 22942
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21990
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 940
telemt_user_connections_total{user="hello"} 794004
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 45224637764 (42.12 GB)
telemt_user_octets_to_client{user="hello"} 371787680916 (346.25 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 123120.2 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1422414
telemt_connections_bad_total 70013
telemt_handshake_timeouts_total 24510
telemt_upstream_connect_attempt_total 91330
telemt_upstream_connect_success_total 88890
telemt_upstream_connect_fail_total 2440
telemt_upstream_connect_attempts_per_request{bucket="1"} 91330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2440
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38420
telemt_me_reconnect_success_total 18008
telemt_me_reader_eof_total 19765
telemt_me_idle_close_by_peer_total 19762
telemt_me_route_drop_no_conn_total 576080
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1157931
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4367
telemt_desync_full_logged_total 1435
telemt_desync_suppressed_total 2932
telemt_desync_frames_bucket_total{bucket="1_2"} 1061
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 1468
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18978
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17988
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 970
telemt_user_connections_total{user="hello"} 1221241
telemt_user_connections_current{user="hello"} 1234
telemt_user_octets_from_client{user="hello"} 19101255626 (17.79 GB)
telemt_user_octets_to_client{user="hello"} 593324111778 (552.58 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 123092.0 (34h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986819
telemt_connections_bad_total 102844
telemt_handshake_timeouts_total 9382
telemt_upstream_connect_attempt_total 48280
telemt_upstream_connect_success_total 47616
telemt_upstream_connect_fail_total 664
telemt_upstream_connect_attempts_per_request{bucket="1"} 48280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 664
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59986
telemt_me_reconnect_success_total 25020
telemt_me_reader_eof_total 27066
telemt_me_idle_close_by_peer_total 27063
telemt_me_route_drop_no_conn_total 315863
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804875
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3588
telemt_desync_full_logged_total 1088
telemt_desync_suppressed_total 2500
telemt_desync_frames_bucket_total{bucket="1_2"} 1065
telemt_desync_frames_bucket_total{bucket="3_10"} 1401
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26499
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25012
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 821353
telemt_user_connections_current{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 15706880020 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 416304456536 (387.71 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 123253.1 (34h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1185562
telemt_connections_bad_total 127250
telemt_handshake_timeouts_total 10404
telemt_upstream_connect_attempt_total 24534
telemt_upstream_connect_success_total 24393
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 24534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29579
telemt_me_reconnect_success_total 18285
telemt_me_reader_eof_total 19813
telemt_me_idle_close_by_peer_total 19811
telemt_me_route_drop_no_conn_total 816426
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1166144
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2198
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 111
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18921
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18271
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 974831
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 15462859900 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 429653689060 (400.15 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 71020.3 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522969
telemt_connections_bad_total 53205
telemt_handshake_timeouts_total 13016
telemt_upstream_connect_attempt_total 25121
telemt_upstream_connect_success_total 24865
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 25121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32809
telemt_me_reconnect_success_total 21197
telemt_me_reader_eof_total 22401
telemt_me_idle_close_by_peer_total 22401
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 127395
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375462
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1645
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 1105
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21785
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21154
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 375214
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 24078098369 (22.42 GB)
telemt_user_octets_to_client{user="hello"} 300465850602 (279.83 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 85
```