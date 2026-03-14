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

# Server Metrics 2026-03-14 10:16:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 182565.0 (50h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710126
telemt_connections_bad_total 33403
telemt_handshake_timeouts_total 13812
telemt_upstream_connect_attempt_total 46439
telemt_upstream_connect_success_total 46204
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5960
telemt_me_reconnect_attempts_total 41446
telemt_me_reconnect_success_total 36741
telemt_me_reader_eof_total 39257
telemt_me_idle_close_by_peer_total 39256
telemt_me_route_drop_no_conn_total 234666
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2413
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1606
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37283
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36721
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 607798
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 17351934094 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 288711583796 (268.88 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 182458.0 (50h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355882
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 3139
telemt_upstream_connect_attempt_total 153841
telemt_upstream_connect_success_total 152494
telemt_upstream_connect_fail_total 1347
telemt_upstream_connect_attempts_per_request{bucket="1"} 153841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2454
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1347
telemt_me_keepalive_timeout_total 5450
telemt_me_reconnect_attempts_total 188395
telemt_me_reconnect_success_total 40108
telemt_me_reader_eof_total 45806
telemt_me_idle_close_by_peer_total 45806
telemt_me_route_drop_no_conn_total 122188
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232796
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 45123
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40091
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5015
telemt_user_connections_total{user="hello"} 335900
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3444223843 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 107377338359 (100.00 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 182421.8 (50h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412843
telemt_connections_bad_total 3261
telemt_handshake_timeouts_total 35765
telemt_upstream_connect_attempt_total 48413
telemt_upstream_connect_success_total 48404
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3785
telemt_me_reconnect_attempts_total 40578
telemt_me_reconnect_success_total 39275
telemt_me_reader_eof_total 42197
telemt_me_idle_close_by_peer_total 42197
telemt_me_route_drop_no_conn_total 149973
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359257
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
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39745
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39254
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 358988
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 13931441316 (12.97 GB)
telemt_user_octets_to_client{user="hello"} 158371204892 (147.49 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 182397.2 (50h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520841
telemt_connections_bad_total 16710
telemt_handshake_timeouts_total 5224
telemt_upstream_connect_attempt_total 78764
telemt_upstream_connect_success_total 68096
telemt_upstream_connect_fail_total 10668
telemt_upstream_connect_attempts_per_request{bucket="1"} 78764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10668
telemt_me_keepalive_timeout_total 5628
telemt_me_reconnect_attempts_total 152278
telemt_me_reconnect_success_total 39981
telemt_me_reader_eof_total 44782
telemt_me_idle_close_by_peer_total 44774
telemt_me_route_drop_no_conn_total 188836
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445664
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 43945
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39971
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3964
telemt_user_connections_total{user="hello"} 464531
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 9978371515 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 192496410056 (179.28 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 132568.8 (36h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220349
telemt_connections_bad_total 33932
telemt_handshake_timeouts_total 1981
telemt_upstream_connect_attempt_total 46657
telemt_upstream_connect_success_total 46197
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 46657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_timeout_total 2756
telemt_me_reconnect_attempts_total 50575
telemt_me_reconnect_success_total 34695
telemt_me_reader_eof_total 37128
telemt_me_idle_close_by_peer_total 37128
telemt_me_route_drop_no_conn_total 66740
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173633
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35511
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34677
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 178390
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2666097629 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 83446711863 (77.72 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 182353.4 (50h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055839
telemt_connections_bad_total 36959
telemt_handshake_timeouts_total 26883
telemt_upstream_connect_attempt_total 38097
telemt_upstream_connect_success_total 37896
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 38097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4870
telemt_me_reconnect_attempts_total 33565
telemt_me_reconnect_success_total 28878
telemt_me_reader_eof_total 30960
telemt_me_idle_close_by_peer_total 30957
telemt_me_route_drop_no_conn_total 494278
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978705
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29388
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28871
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 951317
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 17853657828 (16.63 GB)
telemt_user_octets_to_client{user="hello"} 478606993928 (445.74 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 60
```