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

# Server Metrics 2026-03-14 08:49:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 177376.9 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684313
telemt_connections_bad_total 32581
telemt_handshake_timeouts_total 13361
telemt_upstream_connect_attempt_total 45048
telemt_upstream_connect_success_total 44819
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 45048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5781
telemt_me_reconnect_attempts_total 40291
telemt_me_reconnect_success_total 35593
telemt_me_reader_eof_total 38050
telemt_me_idle_close_by_peer_total 38049
telemt_me_route_drop_no_conn_total 226054
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2250
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1486
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 36120
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35573
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 584215
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 17016628082 (15.85 GB)
telemt_user_octets_to_client{user="hello"} 280309440276 (261.06 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 177269.7 (49h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344211
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3031
telemt_upstream_connect_attempt_total 152511
telemt_upstream_connect_success_total 151193
telemt_upstream_connect_fail_total 1318
telemt_upstream_connect_attempts_per_request{bucket="1"} 152511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2439
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1318
telemt_me_keepalive_timeout_total 5337
telemt_me_reconnect_attempts_total 180542
telemt_me_reconnect_success_total 39073
telemt_me_reader_eof_total 44545
telemt_me_idle_close_by_peer_total 44545
telemt_me_route_drop_no_conn_total 115744
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221606
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_me_writer_removed_unexpected_total 43871
telemt_me_refill_failed_total 4414
telemt_me_writer_restored_same_endpoint_total 39056
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4798
telemt_user_connections_total{user="hello"} 324712
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 3366775271 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 104930635875 (97.72 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 177233.7 (49h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401982
telemt_connections_bad_total 3198
telemt_handshake_timeouts_total 35583
telemt_upstream_connect_attempt_total 46990
telemt_upstream_connect_success_total 46981
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3518
telemt_me_reconnect_attempts_total 39418
telemt_me_reconnect_success_total 38124
telemt_me_reader_eof_total 40954
telemt_me_idle_close_by_peer_total 40954
telemt_me_route_drop_no_conn_total 145282
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349045
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38587
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38103
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 348805
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 13689963968 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 148392013012 (138.20 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 177209.1 (49h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504380
telemt_connections_bad_total 16287
telemt_handshake_timeouts_total 4584
telemt_upstream_connect_attempt_total 77181
telemt_upstream_connect_success_total 66544
telemt_upstream_connect_fail_total 10637
telemt_upstream_connect_attempts_per_request{bucket="1"} 77181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10637
telemt_me_keepalive_timeout_total 5487
telemt_me_reconnect_attempts_total 149822
telemt_me_reconnect_success_total 38702
telemt_me_reader_eof_total 43407
telemt_me_idle_close_by_peer_total 43399
telemt_me_route_drop_no_conn_total 182995
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430939
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1897
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 718
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42616
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38692
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3914
telemt_user_connections_total{user="hello"} 449820
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 9704930979 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 187271014408 (174.41 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 127380.4 (35h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209627
telemt_connections_bad_total 32104
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 44918
telemt_upstream_connect_success_total 44486
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 44918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 2575
telemt_me_reconnect_attempts_total 47978
telemt_me_reconnect_success_total 33259
telemt_me_reader_eof_total 35599
telemt_me_idle_close_by_peer_total 35599
telemt_me_route_drop_no_conn_total 62943
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165162
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34020
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33241
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 169924
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2491556157 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 81059869263 (75.49 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 177165.1 (49h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020357
telemt_connections_bad_total 36391
telemt_handshake_timeouts_total 26399
telemt_upstream_connect_attempt_total 36910
telemt_upstream_connect_success_total 36714
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 36910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 4763
telemt_me_reconnect_attempts_total 32649
telemt_me_reconnect_success_total 27966
telemt_me_reader_eof_total 29999
telemt_me_idle_close_by_peer_total 29996
telemt_me_route_drop_no_conn_total 479493
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 945669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 28463
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27959
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 918295
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 15533648564 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 457852868436 (426.41 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 76
```