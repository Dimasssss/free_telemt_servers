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

# Server Metrics 2026-03-16 00:50:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 95756.0 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417001
telemt_connections_bad_total 5357
telemt_handshake_timeouts_total 14250
telemt_upstream_connect_attempt_total 22916
telemt_upstream_connect_success_total 22806
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 22916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21461
telemt_me_reconnect_success_total 18050
telemt_me_reader_eof_total 19289
telemt_me_idle_close_by_peer_total 19289
telemt_me_route_drop_no_conn_total 492032
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442828
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2188
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1312
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 18355
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 18016
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 381899
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 8238088524 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 281313875392 (261.99 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 95762.5 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173655
telemt_connections_bad_total 2913
telemt_handshake_timeouts_total 14538
telemt_upstream_connect_attempt_total 26124
telemt_upstream_connect_success_total 26049
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 27771
telemt_me_reconnect_success_total 20871
telemt_me_reader_eof_total 22342
telemt_me_idle_close_by_peer_total 22341
telemt_me_route_drop_no_conn_total 70135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149186
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21388
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 20855
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 149447
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 3392786361 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 77911214852 (72.56 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 95755.1 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183530
telemt_connections_bad_total 1980
telemt_handshake_timeouts_total 3567
telemt_upstream_connect_attempt_total 27237
telemt_upstream_connect_success_total 27229
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 29789
telemt_me_reconnect_success_total 22408
telemt_me_reader_eof_total 24109
telemt_me_idle_close_by_peer_total 24108
telemt_me_route_drop_no_conn_total 67706
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153143
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 22857
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22400
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 153018
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 13109872264 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 98670090032 (91.89 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 95754.6 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254290
telemt_connections_bad_total 1211
telemt_handshake_timeouts_total 1644
telemt_upstream_connect_attempt_total 22411
telemt_upstream_connect_success_total 22391
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 22411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 17735
telemt_me_reconnect_success_total 17630
telemt_me_reader_eof_total 18802
telemt_me_idle_close_by_peer_total 18802
telemt_me_route_drop_no_conn_total 91590
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234831
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 875
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17841
telemt_me_writer_restored_same_endpoint_total 17619
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 234743
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 4118682740 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 107377523196 (100.00 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 70826.2 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162663
telemt_connections_bad_total 29462
telemt_handshake_timeouts_total 2829
telemt_upstream_connect_attempt_total 20295
telemt_upstream_connect_success_total 20178
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 20295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 110950
telemt_me_reconnect_success_total 16489
telemt_me_reader_eof_total 17461
telemt_me_idle_close_by_peer_total 17461
telemt_me_route_drop_no_conn_total 51475
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125814
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 16613
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16385
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 125938
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 1810241825 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 44495495759 (41.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 95753.9 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633790
telemt_connections_bad_total 58658
telemt_handshake_timeouts_total 4874
telemt_upstream_connect_attempt_total 20257
telemt_upstream_connect_success_total 20144
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 20257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 16678
telemt_me_reconnect_success_total 15358
telemt_me_reader_eof_total 16372
telemt_me_idle_close_by_peer_total 16372
telemt_me_route_drop_no_conn_total 577489
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671019
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15576
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15331
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 529704
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 12651002852 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 326767407580 (304.33 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 42
```