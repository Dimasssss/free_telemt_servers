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

# Server Metrics 2026-03-13 23:34:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 144072.4 (40h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584809
telemt_connections_bad_total 19373
telemt_handshake_timeouts_total 12835
telemt_upstream_connect_attempt_total 36664
telemt_upstream_connect_success_total 36481
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5160
telemt_me_reconnect_attempts_total 33555
telemt_me_reconnect_success_total 28888
telemt_me_reader_eof_total 30856
telemt_me_idle_close_by_peer_total 30855
telemt_me_route_drop_no_conn_total 192577
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501876
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1623
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 29354
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28872
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 501771
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 15344302126 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 249077304156 (231.97 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 143965.5 (39h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299132
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 1928
telemt_upstream_connect_attempt_total 141057
telemt_upstream_connect_success_total 140006
telemt_upstream_connect_fail_total 1051
telemt_upstream_connect_attempts_per_request{bucket="1"} 141057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1051
telemt_me_keepalive_timeout_total 3745
telemt_me_reconnect_attempts_total 151275
telemt_me_reconnect_success_total 29518
telemt_me_reader_eof_total 34103
telemt_me_idle_close_by_peer_total 34103
telemt_me_route_drop_no_conn_total 91941
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180534
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 33598
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 29501
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4080
telemt_user_connections_total{user="hello"} 283646
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 2981389879 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 89227082863 (83.10 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 143929.1 (39h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349796
telemt_connections_bad_total 2720
telemt_handshake_timeouts_total 31264
telemt_upstream_connect_attempt_total 38190
telemt_upstream_connect_success_total 38184
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2904
telemt_me_reconnect_attempts_total 32231
telemt_me_reconnect_success_total 30979
telemt_me_reader_eof_total 33261
telemt_me_idle_close_by_peer_total 33261
telemt_me_route_drop_no_conn_total 123971
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303543
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 31341
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30959
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 303445
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 12533264692 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 126051300856 (117.39 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 143904.8 (39h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451486
telemt_connections_bad_total 15359
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 65890
telemt_upstream_connect_success_total 55492
telemt_upstream_connect_fail_total 10398
telemt_upstream_connect_attempts_per_request{bucket="1"} 65890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10398
telemt_me_keepalive_timeout_total 5024
telemt_me_reconnect_attempts_total 131770
telemt_me_reconnect_success_total 29293
telemt_me_reader_eof_total 33335
telemt_me_idle_close_by_peer_total 33327
telemt_me_route_drop_no_conn_total 158361
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381758
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 32859
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 29283
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3566
telemt_user_connections_total{user="hello"} 400600
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 9018982427 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 153037852040 (142.53 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 94076.4 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157864
telemt_connections_bad_total 23243
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 34837
telemt_upstream_connect_success_total 34512
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 34837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1340
telemt_me_reconnect_attempts_total 38324
telemt_me_reconnect_success_total 24918
telemt_me_reader_eof_total 26643
telemt_me_idle_close_by_peer_total 26643
telemt_me_route_drop_no_conn_total 47824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123420
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 25574
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24900
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 128275
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 1566335573 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 61340074883 (57.13 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 143861.0 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857108
telemt_connections_bad_total 27282
telemt_handshake_timeouts_total 25199
telemt_upstream_connect_attempt_total 29693
telemt_upstream_connect_success_total 29535
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 29693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 3400
telemt_me_reconnect_attempts_total 27073
telemt_me_reconnect_success_total 22410
telemt_me_reader_eof_total 24012
telemt_me_idle_close_by_peer_total 24009
telemt_me_route_drop_no_conn_total 408528
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800217
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 22849
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22403
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 773071
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 13275857436 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 394415668052 (367.33 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 22
```