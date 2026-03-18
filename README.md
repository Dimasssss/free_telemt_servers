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

# Server Metrics 2026-03-18 13:50:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 18581.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691569
telemt_connections_bad_total 34522
telemt_handshake_timeouts_total 18927
telemt_upstream_connect_attempt_total 66544
telemt_upstream_connect_success_total 65586
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 66544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514314
telemt_me_reconnect_success_total 2662
telemt_me_reader_eof_total 2831
telemt_me_idle_close_by_peer_total 2829
telemt_me_route_drop_no_conn_total 391513
telemt_me_route_drop_channel_closed_total 150
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533133
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2329
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1522
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 806
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2834
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2557
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 591302
telemt_user_connections_current{user="hello"} 1725
telemt_user_octets_from_client{user="hello"} 8231764080 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 151582637925 (141.17 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 18613.2 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1826203
telemt_connections_bad_total 131129
telemt_handshake_timeouts_total 41094
telemt_upstream_connect_attempt_total 3287
telemt_upstream_connect_success_total 3275
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3413
telemt_me_reconnect_success_total 2267
telemt_me_reader_eof_total 2352
telemt_me_idle_close_by_peer_total 2351
telemt_me_route_drop_no_conn_total 1436252
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1564118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4858
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3333
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1966
telemt_desync_frames_bucket_total{bucket="gt_10"} 1912
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2318
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2266
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1563111
telemt_user_connections_current{user="hello"} 4551
telemt_user_octets_from_client{user="hello"} 37319211368 (34.76 GB)
telemt_user_octets_to_client{user="hello"} 486058813552 (452.68 GB)
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 660
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 18527.6 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1340940
telemt_connections_bad_total 101683
telemt_handshake_timeouts_total 29927
telemt_upstream_connect_attempt_total 11822
telemt_upstream_connect_success_total 11822
telemt_upstream_connect_attempts_per_request{bucket="1"} 11822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 612231
telemt_me_reconnect_success_total 2626
telemt_me_reader_eof_total 2775
telemt_me_idle_close_by_peer_total 2774
telemt_me_route_drop_no_conn_total 658846
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3256
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2172
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 1174
telemt_desync_frames_bucket_total{bucket="gt_10"} 1179
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2765
telemt_me_refill_failed_total 19794
telemt_me_writer_restored_same_endpoint_total 2591
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1055732
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 13518731059 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 427919671604 (398.53 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 18558.0 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2140786
telemt_connections_bad_total 33838
telemt_handshake_timeouts_total 177258
telemt_upstream_connect_attempt_total 12650
telemt_upstream_connect_success_total 12436
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 12650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2835314
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 3278108
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1764729
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3779
telemt_desync_full_logged_total 1114
telemt_desync_suppressed_total 2665
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1593
telemt_desync_frames_bucket_total{bucket="gt_10"} 1228
telemt_me_writer_removed_unexpected_total 1939
telemt_me_refill_failed_total 100304
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1783175
telemt_user_connections_current{user="hello"} 2884
telemt_user_octets_from_client{user="hello"} 40516698714 (37.73 GB)
telemt_user_octets_to_client{user="hello"} 260644169609 (242.74 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 891
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 18452.6 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453058
telemt_connections_bad_total 104469
telemt_handshake_timeouts_total 23900
telemt_upstream_connect_attempt_total 14814
telemt_upstream_connect_success_total 14786
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986607
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2273
telemt_me_idle_close_by_peer_total 2273
telemt_me_route_drop_no_conn_total 1322174
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1209688
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3672
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2419
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 1419
telemt_desync_frames_bucket_total{bucket="gt_10"} 1683
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2235
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2056
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1211597
telemt_user_connections_current{user="hello"} 3181
telemt_user_octets_from_client{user="hello"} 19371854279 (18.04 GB)
telemt_user_octets_to_client{user="hello"} 431179005409 (401.57 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1034
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 18338.1 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411740
telemt_connections_bad_total 46281
telemt_handshake_timeouts_total 3006
telemt_upstream_connect_attempt_total 3396
telemt_upstream_connect_success_total 3396
telemt_upstream_connect_attempts_per_request{bucket="1"} 3396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8841
telemt_me_reconnect_success_total 2387
telemt_me_reader_eof_total 2642
telemt_me_idle_close_by_peer_total 2641
telemt_me_route_drop_no_conn_total 229611
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 907
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 585
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2612
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2378
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 334551
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 5091716472 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 70000863040 (65.19 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 18408.8 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175013
telemt_connections_bad_total 127300
telemt_handshake_timeouts_total 23540
telemt_upstream_connect_attempt_total 3419
telemt_upstream_connect_success_total 3388
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 4855
telemt_me_reconnect_success_total 2377
telemt_me_reader_eof_total 2510
telemt_me_idle_close_by_peer_total 2510
telemt_me_route_drop_no_conn_total 684673
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931962
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3127
telemt_desync_full_logged_total 1043
telemt_desync_suppressed_total 2084
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 1496
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2476
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 2367
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 931310
telemt_user_connections_current{user="hello"} 2974
telemt_user_octets_from_client{user="hello"} 18878803796 (17.58 GB)
telemt_user_octets_to_client{user="hello"} 423959543680 (394.84 GB)
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 395
```