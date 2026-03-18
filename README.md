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

# Server Metrics 2026-03-18 01:42:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 111424.1 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293709
telemt_connections_bad_total 9650
telemt_handshake_timeouts_total 32535
telemt_upstream_connect_attempt_total 24836
telemt_upstream_connect_success_total 24334
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 24836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33638
telemt_me_reconnect_success_total 16500
telemt_me_reader_eof_total 17915
telemt_me_idle_close_by_peer_total 17914
telemt_me_route_drop_no_conn_total 564443
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1190594
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7619
telemt_desync_full_logged_total 2244
telemt_desync_suppressed_total 5375
telemt_desync_frames_bucket_total{bucket="1_2"} 2042
telemt_desync_frames_bucket_total{bucket="3_10"} 2888
telemt_desync_frames_bucket_total{bucket="gt_10"} 2689
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17280
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16478
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 1184806
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 22945098291 (21.37 GB)
telemt_user_octets_to_client{user="hello"} 421547716927 (392.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 111675.7 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370513
telemt_connections_bad_total 64185
telemt_handshake_timeouts_total 46721
telemt_upstream_connect_attempt_total 467528
telemt_upstream_connect_success_total 465961
telemt_upstream_connect_fail_total 1567
telemt_upstream_connect_attempts_per_request{bucket="1"} 467528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1567
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122913
telemt_me_reconnect_success_total 17475
telemt_me_reader_eof_total 19622
telemt_me_idle_close_by_peer_total 19609
telemt_me_route_drop_no_conn_total 353362
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747523
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3474
telemt_desync_full_logged_total 1170
telemt_desync_suppressed_total 2304
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 1439
telemt_desync_frames_bucket_total{bucket="gt_10"} 1355
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 19038
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17457
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1563
telemt_user_connections_total{user="hello"} 1189873
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 16148665377 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 414904257962 (386.41 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 111451.4 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818575
telemt_connections_bad_total 55407
telemt_handshake_timeouts_total 24337
telemt_upstream_connect_attempt_total 26088
telemt_upstream_connect_success_total 25936
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41036
telemt_me_reconnect_success_total 20346
telemt_me_reader_eof_total 22145
telemt_me_idle_close_by_peer_total 22138
telemt_me_route_drop_no_conn_total 327908
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693566
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2192
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21267
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20334
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 921
telemt_user_connections_total{user="hello"} 691686
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 41007353504 (38.19 GB)
telemt_user_octets_to_client{user="hello"} 305679617144 (284.69 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 111510.9 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302021
telemt_connections_bad_total 56578
telemt_handshake_timeouts_total 22021
telemt_upstream_connect_attempt_total 88894
telemt_upstream_connect_success_total 86485
telemt_upstream_connect_fail_total 2409
telemt_upstream_connect_attempts_per_request{bucket="1"} 88894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13626
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2409
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36565
telemt_me_reconnect_success_total 16171
telemt_me_reader_eof_total 17824
telemt_me_idle_close_by_peer_total 17822
telemt_me_route_drop_no_conn_total 534678
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1057961
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3957
telemt_desync_full_logged_total 1310
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 17113
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16160
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 942
telemt_user_connections_total{user="hello"} 1121462
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 17585835310 (16.38 GB)
telemt_user_octets_to_client{user="hello"} 529436402066 (493.08 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 111483.0 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859995
telemt_connections_bad_total 99955
telemt_handshake_timeouts_total 6847
telemt_upstream_connect_attempt_total 45659
telemt_upstream_connect_success_total 45033
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 45659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57962
telemt_me_reconnect_success_total 23000
telemt_me_reader_eof_total 24944
telemt_me_idle_close_by_peer_total 24942
telemt_me_route_drop_no_conn_total 273396
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693904
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3202
telemt_desync_full_logged_total 953
telemt_desync_suppressed_total 2249
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24461
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22992
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1461
telemt_user_connections_total{user="hello"} 710507
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 13752956164 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 352595326452 (328.38 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 111643.7 (31h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106504
telemt_connections_bad_total 114243
telemt_handshake_timeouts_total 9689
telemt_upstream_connect_attempt_total 22185
telemt_upstream_connect_success_total 22057
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27791
telemt_me_reconnect_success_total 16503
telemt_me_reader_eof_total 17902
telemt_me_idle_close_by_peer_total 17900
telemt_me_route_drop_no_conn_total 754711
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1077119
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 98
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17118
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16489
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 912091
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 14825011400 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 393598800416 (366.57 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 59411.0 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413946
telemt_connections_bad_total 44712
telemt_handshake_timeouts_total 10973
telemt_upstream_connect_attempt_total 22077
telemt_upstream_connect_success_total 21871
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 22077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30376
telemt_me_reconnect_success_total 18770
telemt_me_reader_eof_total 19848
telemt_me_idle_close_by_peer_total 19848
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 102606
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300341
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1266
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 560
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19342
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18734
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 300277
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 22491091073 (20.95 GB)
telemt_user_octets_to_client{user="hello"} 252895575706 (235.53 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 30
```