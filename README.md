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

# Server Metrics 2026-03-14 09:45:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 180734.0 (50h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700635
telemt_connections_bad_total 32737
telemt_handshake_timeouts_total 13648
telemt_upstream_connect_attempt_total 45879
telemt_upstream_connect_success_total 45646
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 45879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5901
telemt_me_reconnect_attempts_total 40977
telemt_me_reconnect_success_total 36275
telemt_me_reader_eof_total 38782
telemt_me_idle_close_by_peer_total 38781
telemt_me_route_drop_no_conn_total 231394
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599551
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2379
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1586
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 36809
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36255
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 599429
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 17267772074 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 286804777352 (267.11 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 180626.9 (50h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352325
telemt_connections_bad_total 2810
telemt_handshake_timeouts_total 3099
telemt_upstream_connect_attempt_total 153461
telemt_upstream_connect_success_total 152115
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5404
telemt_me_reconnect_attempts_total 186760
telemt_me_reconnect_success_total 39819
telemt_me_reader_eof_total 45463
telemt_me_idle_close_by_peer_total 45463
telemt_me_route_drop_no_conn_total 120152
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_me_writer_removed_unexpected_total 44790
telemt_me_refill_failed_total 4585
telemt_me_writer_restored_same_endpoint_total 39802
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4971
telemt_user_connections_total{user="hello"} 332500
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3425885727 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 106586925323 (99.27 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 180590.4 (50h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408706
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 35659
telemt_upstream_connect_attempt_total 47884
telemt_upstream_connect_success_total 47875
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3714
telemt_me_reconnect_attempts_total 40138
telemt_me_reconnect_success_total 38836
telemt_me_reader_eof_total 41745
telemt_me_idle_close_by_peer_total 41745
telemt_me_route_drop_no_conn_total 148346
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355420
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
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 39305
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38815
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 355146
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 13762084248 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 157006585184 (146.22 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 180565.9 (50h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516063
telemt_connections_bad_total 16708
telemt_handshake_timeouts_total 5184
telemt_upstream_connect_attempt_total 78279
telemt_upstream_connect_success_total 67619
telemt_upstream_connect_fail_total 10660
telemt_upstream_connect_attempts_per_request{bucket="1"} 78279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10660
telemt_me_keepalive_timeout_total 5557
telemt_me_reconnect_attempts_total 151887
telemt_me_reconnect_success_total 39594
telemt_me_reader_eof_total 44358
telemt_me_idle_close_by_peer_total 44350
telemt_me_route_drop_no_conn_total 186866
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441066
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1964
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1384
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 759
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43554
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39584
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3960
telemt_user_connections_total{user="hello"} 459936
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 9883444415 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 191007777584 (177.89 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 130737.5 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216681
telemt_connections_bad_total 33377
telemt_handshake_timeouts_total 1960
telemt_upstream_connect_attempt_total 46203
telemt_upstream_connect_success_total 45752
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 46203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2676
telemt_me_reconnect_attempts_total 50216
telemt_me_reconnect_success_total 34341
telemt_me_reader_eof_total 36752
telemt_me_idle_close_by_peer_total 36752
telemt_me_route_drop_no_conn_total 65229
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170611
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 756
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 35147
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34323
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 806
telemt_user_connections_total{user="hello"} 175370
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2640731677 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 82684470559 (77.01 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 180522.3 (50h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043357
telemt_connections_bad_total 36910
telemt_handshake_timeouts_total 26777
telemt_upstream_connect_attempt_total 37668
telemt_upstream_connect_success_total 37468
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 37668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 4848
telemt_me_reconnect_attempts_total 33225
telemt_me_reconnect_success_total 28540
telemt_me_reader_eof_total 30607
telemt_me_idle_close_by_peer_total 30604
telemt_me_route_drop_no_conn_total 488737
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966855
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 29046
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28533
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 939470
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 17241671496 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 469796904540 (437.53 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 71
```