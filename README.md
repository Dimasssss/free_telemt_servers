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

# Server Metrics 2026-03-14 09:25:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 179512.1 (49h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694670
telemt_connections_bad_total 32629
telemt_handshake_timeouts_total 13538
telemt_upstream_connect_attempt_total 45570
telemt_upstream_connect_success_total 45339
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 45570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5867
telemt_me_reconnect_attempts_total 40713
telemt_me_reconnect_success_total 36013
telemt_me_reader_eof_total 38496
telemt_me_idle_close_by_peer_total 38495
telemt_me_route_drop_no_conn_total 229624
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594017
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2361
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 36542
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35993
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 593901
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 17210684482 (16.03 GB)
telemt_user_octets_to_client{user="hello"} 285621541204 (266.01 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 179405.2 (49h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349623
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3043
telemt_upstream_connect_attempt_total 153180
telemt_upstream_connect_success_total 151838
telemt_upstream_connect_fail_total 1342
telemt_upstream_connect_attempts_per_request{bucket="1"} 153180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1342
telemt_me_keepalive_timeout_total 5376
telemt_me_reconnect_attempts_total 185151
telemt_me_reconnect_success_total 39586
telemt_me_reader_eof_total 45186
telemt_me_idle_close_by_peer_total 45186
telemt_me_route_drop_no_conn_total 118649
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226842
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44513
telemt_me_refill_failed_total 4542
telemt_me_writer_restored_same_endpoint_total 39569
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4927
telemt_user_connections_total{user="hello"} 329946
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 3410552679 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 105904073471 (98.63 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 179368.8 (49h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406260
telemt_connections_bad_total 3206
telemt_handshake_timeouts_total 35641
telemt_upstream_connect_attempt_total 47607
telemt_upstream_connect_success_total 47598
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3676
telemt_me_reconnect_attempts_total 39904
telemt_me_reconnect_success_total 38605
telemt_me_reader_eof_total 41498
telemt_me_idle_close_by_peer_total 41498
telemt_me_route_drop_no_conn_total 147334
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 39070
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38584
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 352828
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 13743930984 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 155941044304 (145.23 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 179344.3 (49h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511252
telemt_connections_bad_total 16445
telemt_handshake_timeouts_total 4650
telemt_upstream_connect_attempt_total 77836
telemt_upstream_connect_success_total 67181
telemt_upstream_connect_fail_total 10655
telemt_upstream_connect_attempts_per_request{bucket="1"} 77836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10655
telemt_me_keepalive_timeout_total 5547
telemt_me_reconnect_attempts_total 150328
telemt_me_reconnect_success_total 39203
telemt_me_reader_eof_total 43927
telemt_me_idle_close_by_peer_total 43919
telemt_me_route_drop_no_conn_total 185398
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437203
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1947
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1372
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43123
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 39193
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3920
telemt_user_connections_total{user="hello"} 456086
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 9826417115 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 190270296052 (177.20 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 129515.8 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213960
telemt_connections_bad_total 33040
telemt_handshake_timeouts_total 1924
telemt_upstream_connect_attempt_total 45714
telemt_upstream_connect_success_total 45270
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 45714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 2652
telemt_me_reconnect_attempts_total 48670
telemt_me_reconnect_success_total 33948
telemt_me_reader_eof_total 36295
telemt_me_idle_close_by_peer_total 36295
telemt_me_route_drop_no_conn_total 64407
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168311
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34716
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33930
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 173072
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2629420133 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 81932371423 (76.31 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 179300.7 (49h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034743
telemt_connections_bad_total 36844
telemt_handshake_timeouts_total 26717
telemt_upstream_connect_attempt_total 37411
telemt_upstream_connect_success_total 37212
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4829
telemt_me_reconnect_attempts_total 33017
telemt_me_reconnect_success_total 28332
telemt_me_reader_eof_total 30395
telemt_me_idle_close_by_peer_total 30392
telemt_me_route_drop_no_conn_total 485419
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 958700
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 28834
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28325
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 931317
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 17095421448 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 463998738880 (432.13 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 64
```