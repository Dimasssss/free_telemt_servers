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

# Server Metrics 2026-03-18 04:30:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 121506.1 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387600
telemt_connections_bad_total 10538
telemt_handshake_timeouts_total 34090
telemt_upstream_connect_attempt_total 26675
telemt_upstream_connect_success_total 26163
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34991
telemt_me_reconnect_success_total 17845
telemt_me_reader_eof_total 19357
telemt_me_idle_close_by_peer_total 19356
telemt_me_route_drop_no_conn_total 593270
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1277232
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7970
telemt_desync_full_logged_total 2381
telemt_desync_suppressed_total 5589
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 2811
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18645
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17823
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 800
telemt_user_connections_total{user="hello"} 1271440
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 25610816203 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 449591842283 (418.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 121757.4 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1495777
telemt_connections_bad_total 71106
telemt_handshake_timeouts_total 48545
telemt_upstream_connect_attempt_total 470116
telemt_upstream_connect_success_total 468497
telemt_upstream_connect_fail_total 1619
telemt_upstream_connect_attempts_per_request{bucket="1"} 470116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1619
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126229
telemt_me_reconnect_success_total 19502
telemt_me_reader_eof_total 21760
telemt_me_idle_close_by_peer_total 21747
telemt_me_route_drop_no_conn_total 388827
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860045
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3851
telemt_desync_full_logged_total 1344
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 753
telemt_desync_frames_bucket_total{bucket="3_10"} 1582
telemt_desync_frames_bucket_total{bucket="gt_10"} 1516
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 21121
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19484
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 1302365
telemt_user_connections_current{user="hello"} 1230
telemt_user_octets_from_client{user="hello"} 17661833529 (16.45 GB)
telemt_user_octets_to_client{user="hello"} 481565114710 (448.49 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 121533.5 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935756
telemt_connections_bad_total 65959
telemt_handshake_timeouts_total 27163
telemt_upstream_connect_attempt_total 28038
telemt_upstream_connect_success_total 27878
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 28038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42495
telemt_me_reconnect_success_total 21797
telemt_me_reader_eof_total 23695
telemt_me_idle_close_by_peer_total 23688
telemt_me_route_drop_no_conn_total 354436
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2479
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1656
telemt_desync_frames_bucket_total{bucket="1_2"} 705
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22732
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21785
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 772663
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 44969455244 (41.88 GB)
telemt_user_octets_to_client{user="hello"} 356341026268 (331.87 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 121592.7 (33h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1393745
telemt_connections_bad_total 67400
telemt_handshake_timeouts_total 24358
telemt_upstream_connect_attempt_total 91092
telemt_upstream_connect_success_total 88655
telemt_upstream_connect_fail_total 2437
telemt_upstream_connect_attempts_per_request{bucket="1"} 91092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38229
telemt_me_reconnect_success_total 17820
telemt_me_reader_eof_total 19562
telemt_me_idle_close_by_peer_total 19559
telemt_me_route_drop_no_conn_total 567671
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1133489
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4223
telemt_desync_full_logged_total 1390
telemt_desync_suppressed_total 2833
telemt_desync_frames_bucket_total{bucket="1_2"} 1047
telemt_desync_frames_bucket_total{bucket="3_10"} 1762
telemt_desync_frames_bucket_total{bucket="gt_10"} 1414
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18785
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17800
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 965
telemt_user_connections_total{user="hello"} 1196795
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 18625616746 (17.35 GB)
telemt_user_octets_to_client{user="hello"} 577387583250 (537.73 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 121564.6 (33h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958708
telemt_connections_bad_total 102566
telemt_handshake_timeouts_total 8586
telemt_upstream_connect_attempt_total 47983
telemt_upstream_connect_success_total 47322
telemt_upstream_connect_fail_total 661
telemt_upstream_connect_attempts_per_request{bucket="1"} 47983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 661
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59757
telemt_me_reconnect_success_total 24790
telemt_me_reader_eof_total 26818
telemt_me_idle_close_by_peer_total 26815
telemt_me_route_drop_no_conn_total 306369
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3496
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2438
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1073
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26267
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24782
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1477
telemt_user_connections_total{user="hello"} 796512
telemt_user_connections_current{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 15239470608 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 403602771464 (375.88 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 121726.0 (33h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1173044
telemt_connections_bad_total 126918
telemt_handshake_timeouts_total 10328
telemt_upstream_connect_attempt_total 24263
telemt_upstream_connect_success_total 24124
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29353
telemt_me_reconnect_success_total 18059
telemt_me_reader_eof_total 19580
telemt_me_idle_close_by_peer_total 19578
telemt_me_route_drop_no_conn_total 811636
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1155027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2149
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 110
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18693
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18045
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 963717
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 15357343688 (14.30 GB)
telemt_user_octets_to_client{user="hello"} 425159147548 (395.96 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 69492.9 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502888
telemt_connections_bad_total 52287
telemt_handshake_timeouts_total 12816
telemt_upstream_connect_attempt_total 24802
telemt_upstream_connect_success_total 24548
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 24802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32535
telemt_me_reconnect_success_total 20924
telemt_me_reader_eof_total 22116
telemt_me_idle_close_by_peer_total 22116
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 120597
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359258
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1576
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21511
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20881
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 359051
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 23462608401 (21.85 GB)
telemt_user_octets_to_client{user="hello"} 291763040518 (271.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 87
```