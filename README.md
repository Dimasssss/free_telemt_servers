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

# Server Metrics 2026-03-13 21:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 134905.2 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566137
telemt_connections_bad_total 15914
telemt_handshake_timeouts_total 12678
telemt_upstream_connect_attempt_total 34224
telemt_upstream_connect_success_total 34051
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5067
telemt_me_reconnect_attempts_total 31591
telemt_me_reconnect_success_total 26937
telemt_me_reader_eof_total 28748
telemt_me_idle_close_by_peer_total 28747
telemt_me_route_drop_no_conn_total 187096
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487739
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 27385
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26921
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 487634
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 14695231534 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 235467506192 (219.30 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 134798.2 (37h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287006
telemt_connections_bad_total 2135
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 137047
telemt_upstream_connect_success_total 136055
telemt_upstream_connect_fail_total 992
telemt_upstream_connect_attempts_per_request{bucket="1"} 137047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2407
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 992
telemt_me_keepalive_timeout_total 3663
telemt_me_reconnect_attempts_total 143559
telemt_me_reconnect_success_total 26485
telemt_me_reader_eof_total 30875
telemt_me_idle_close_by_peer_total 30875
telemt_me_route_drop_no_conn_total 84090
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 30389
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26468
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3904
telemt_user_connections_total{user="hello"} 272236
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2826833173 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 82680254801 (77.00 GB)
telemt_user_msgs_from_client{user="hello"} 1679604
telemt_user_msgs_to_client{user="hello"} 9336624
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 134761.8 (37h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333821
telemt_connections_bad_total 2651
telemt_handshake_timeouts_total 25359
telemt_upstream_connect_attempt_total 35846
telemt_upstream_connect_success_total 35841
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2823
telemt_me_reconnect_attempts_total 30322
telemt_me_reconnect_success_total 29081
telemt_me_reader_eof_total 31180
telemt_me_idle_close_by_peer_total 31180
telemt_me_route_drop_no_conn_total 119512
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294065
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
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 29409
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29061
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 293967
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 11955882700 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 122691721400 (114.27 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 134737.5 (37h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439601
telemt_connections_bad_total 15245
telemt_handshake_timeouts_total 4194
telemt_upstream_connect_attempt_total 63697
telemt_upstream_connect_success_total 53371
telemt_upstream_connect_fail_total 10326
telemt_upstream_connect_attempts_per_request{bucket="1"} 63697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10326
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 124715
telemt_me_reconnect_success_total 27624
telemt_me_reader_eof_total 31435
telemt_me_idle_close_by_peer_total 31428
telemt_me_route_drop_no_conn_total 152720
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370406
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1547
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31006
telemt_me_refill_failed_total 3028
telemt_me_writer_restored_same_endpoint_total 27614
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3382
telemt_user_connections_total{user="hello"} 389263
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 8776850815 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 143296722328 (133.46 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84909.0 (23h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145238
telemt_connections_bad_total 20468
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32004
telemt_upstream_connect_success_total 31697
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 32004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 1285
telemt_me_reconnect_attempts_total 35944
telemt_me_reconnect_success_total 22550
telemt_me_reader_eof_total 24155
telemt_me_idle_close_by_peer_total 24155
telemt_me_route_drop_no_conn_total 44874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113780
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 23181
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22532
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 631
telemt_user_connections_total{user="hello"} 118674
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 1375483949 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 54165860199 (50.45 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 134693.5 (37h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820651
telemt_connections_bad_total 25369
telemt_handshake_timeouts_total 25051
telemt_upstream_connect_attempt_total 27751
telemt_upstream_connect_success_total 27605
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 3098
telemt_me_reconnect_attempts_total 25577
telemt_me_reconnect_success_total 20927
telemt_me_reader_eof_total 22443
telemt_me_idle_close_by_peer_total 22440
telemt_me_route_drop_no_conn_total 391284
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21352
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20920
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 742185
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 12961991484 (12.07 GB)
telemt_user_octets_to_client{user="hello"} 368973360360 (343.63 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 46
```