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

# Server Metrics 2026-03-14 12:48:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 191723.9 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761309
telemt_connections_bad_total 36386
telemt_handshake_timeouts_total 14561
telemt_upstream_connect_attempt_total 48547
telemt_upstream_connect_success_total 48306
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 48547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6342
telemt_me_reconnect_attempts_total 44159
telemt_me_reconnect_success_total 38389
telemt_me_reader_eof_total 41039
telemt_me_idle_close_by_peer_total 41038
telemt_me_route_drop_no_conn_total 249868
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652921
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2836
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 1894
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1063
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 38980
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38369
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 652826
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 18053628822 (16.81 GB)
telemt_user_octets_to_client{user="hello"} 311197343776 (289.83 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 191617.7 (53h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376307
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3369
telemt_upstream_connect_attempt_total 158625
telemt_upstream_connect_success_total 157217
telemt_upstream_connect_fail_total 1408
telemt_upstream_connect_attempts_per_request{bucket="1"} 158625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2536
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1408
telemt_me_keepalive_timeout_total 5730
telemt_me_reconnect_attempts_total 197207
telemt_me_reconnect_success_total 42572
telemt_me_reader_eof_total 48511
telemt_me_idle_close_by_peer_total 48511
telemt_me_route_drop_no_conn_total 129781
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47823
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5251
telemt_user_connections_total{user="hello"} 354484
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3593897491 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 113740920410 (105.93 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 191581.1 (53h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432626
telemt_connections_bad_total 3335
telemt_handshake_timeouts_total 36760
telemt_upstream_connect_attempt_total 51205
telemt_upstream_connect_success_total 51196
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4352
telemt_me_reconnect_attempts_total 42879
telemt_me_reconnect_success_total 41556
telemt_me_reader_eof_total 44623
telemt_me_idle_close_by_peer_total 44623
telemt_me_route_drop_no_conn_total 158914
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376980
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 42052
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41535
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 376714
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 16249407890 (15.13 GB)
telemt_user_octets_to_client{user="hello"} 166398727027 (154.97 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 191556.8 (53h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552540
telemt_connections_bad_total 16785
telemt_handshake_timeouts_total 5350
telemt_upstream_connect_attempt_total 81530
telemt_upstream_connect_success_total 70802
telemt_upstream_connect_fail_total 10728
telemt_upstream_connect_attempts_per_request{bucket="1"} 81530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10728
telemt_me_keepalive_timeout_total 5860
telemt_me_reconnect_attempts_total 160489
telemt_me_reconnect_success_total 42229
telemt_me_reader_eof_total 47257
telemt_me_idle_close_by_peer_total 47249
telemt_me_route_drop_no_conn_total 199654
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474300
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2203
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1555
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46407
telemt_me_refill_failed_total 3687
telemt_me_writer_restored_same_endpoint_total 42219
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4178
telemt_user_connections_total{user="hello"} 493159
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 10385619575 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 203628513696 (189.64 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 141728.4 (39h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241798
telemt_connections_bad_total 38798
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 49853
telemt_upstream_connect_success_total 49346
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 49853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_timeout_total 3155
telemt_me_reconnect_attempts_total 58275
telemt_me_reconnect_success_total 37392
telemt_me_reader_eof_total 40068
telemt_me_idle_close_by_peer_total 40068
telemt_me_route_drop_no_conn_total 73784
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189378
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38394
telemt_me_refill_failed_total 648
telemt_me_writer_restored_same_endpoint_total 37374
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1002
telemt_user_connections_total{user="hello"} 194134
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2792748357 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 89262850703 (83.13 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 191513.1 (53h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120024
telemt_connections_bad_total 38022
telemt_handshake_timeouts_total 27432
telemt_upstream_connect_attempt_total 39848
telemt_upstream_connect_success_total 39640
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 39848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 5240
telemt_me_reconnect_attempts_total 34872
telemt_me_reconnect_success_total 30174
telemt_me_reader_eof_total 32353
telemt_me_idle_close_by_peer_total 32350
telemt_me_route_drop_no_conn_total 527398
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1038778
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30703
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30167
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1011398
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 21606004240 (20.12 GB)
telemt_user_octets_to_client{user="hello"} 513142940272 (477.90 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 62
```