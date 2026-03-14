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

# Server Metrics 2026-03-14 12:43:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 191418.4 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759715
telemt_connections_bad_total 36284
telemt_handshake_timeouts_total 14549
telemt_upstream_connect_attempt_total 48508
telemt_upstream_connect_success_total 48267
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 48508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6342
telemt_me_reconnect_attempts_total 44123
telemt_me_reconnect_success_total 38353
telemt_me_reader_eof_total 41003
telemt_me_idle_close_by_peer_total 41002
telemt_me_route_drop_no_conn_total 249416
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651512
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2815
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1877
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 38944
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38333
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 651420
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 17974002358 (16.74 GB)
telemt_user_octets_to_client{user="hello"} 310922987200 (289.57 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 191311.1 (53h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375658
telemt_connections_bad_total 2877
telemt_handshake_timeouts_total 3361
telemt_upstream_connect_attempt_total 158538
telemt_upstream_connect_success_total 157130
telemt_upstream_connect_fail_total 1408
telemt_upstream_connect_attempts_per_request{bucket="1"} 158538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2536
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1408
telemt_me_keepalive_timeout_total 5725
telemt_me_reconnect_attempts_total 197120
telemt_me_reconnect_success_total 42487
telemt_me_reader_eof_total 48420
telemt_me_idle_close_by_peer_total 48420
telemt_me_route_drop_no_conn_total 129582
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249000
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
telemt_me_writer_removed_unexpected_total 47732
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42469
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5245
telemt_user_connections_total{user="hello"} 353893
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 3588054587 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 113578278586 (105.78 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 191274.6 (53h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432128
telemt_connections_bad_total 3335
telemt_handshake_timeouts_total 36750
telemt_upstream_connect_attempt_total 51106
telemt_upstream_connect_success_total 51097
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4350
telemt_me_reconnect_attempts_total 42780
telemt_me_reconnect_success_total 41457
telemt_me_reader_eof_total 44524
telemt_me_idle_close_by_peer_total 44524
telemt_me_route_drop_no_conn_total 158731
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376511
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
telemt_me_writer_removed_unexpected_total 41953
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41436
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 376245
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 16243554062 (15.13 GB)
telemt_user_octets_to_client{user="hello"} 165950594991 (154.55 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 191250.3 (53h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551562
telemt_connections_bad_total 16784
telemt_handshake_timeouts_total 5343
telemt_upstream_connect_attempt_total 81483
telemt_upstream_connect_success_total 70755
telemt_upstream_connect_fail_total 10728
telemt_upstream_connect_attempts_per_request{bucket="1"} 81483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10728
telemt_me_keepalive_timeout_total 5860
telemt_me_reconnect_attempts_total 160442
telemt_me_reconnect_success_total 42182
telemt_me_reader_eof_total 47210
telemt_me_idle_close_by_peer_total 47202
telemt_me_route_drop_no_conn_total 199270
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473389
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2202
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1555
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46360
telemt_me_refill_failed_total 3687
telemt_me_writer_restored_same_endpoint_total 42172
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4178
telemt_user_connections_total{user="hello"} 492249
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 10378047135 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 203317207236 (189.35 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 141421.8 (39h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241155
telemt_connections_bad_total 38697
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 49764
telemt_upstream_connect_success_total 49260
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 49764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_timeout_total 3153
telemt_me_reconnect_attempts_total 56984
telemt_me_reconnect_success_total 37318
telemt_me_reader_eof_total 39955
telemt_me_idle_close_by_peer_total 39955
telemt_me_route_drop_no_conn_total 73518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188851
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 663
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38281
telemt_me_refill_failed_total 610
telemt_me_writer_restored_same_endpoint_total 37300
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 963
telemt_user_connections_total{user="hello"} 193607
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2788604881 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 89188507907 (83.06 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 191206.5 (53h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117825
telemt_connections_bad_total 38003
telemt_handshake_timeouts_total 27411
telemt_upstream_connect_attempt_total 39817
telemt_upstream_connect_success_total 39609
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 39817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 5237
telemt_me_reconnect_attempts_total 34841
telemt_me_reconnect_success_total 30143
telemt_me_reader_eof_total 32322
telemt_me_idle_close_by_peer_total 32319
telemt_me_route_drop_no_conn_total 526409
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30672
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30136
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1009307
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 21588469960 (20.11 GB)
telemt_user_octets_to_client{user="hello"} 511276439832 (476.16 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 88
```