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

# Server Metrics 2026-03-14 13:04:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 192642.1 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766467
telemt_connections_bad_total 36825
telemt_handshake_timeouts_total 14593
telemt_upstream_connect_attempt_total 48744
telemt_upstream_connect_success_total 48502
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 48744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6352
telemt_me_reconnect_attempts_total 44306
telemt_me_reconnect_success_total 38535
telemt_me_reader_eof_total 41196
telemt_me_idle_close_by_peer_total 41195
telemt_me_route_drop_no_conn_total 252035
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657501
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2871
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 1914
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 39128
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38515
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 657406
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 18118312138 (16.87 GB)
telemt_user_octets_to_client{user="hello"} 312196671208 (290.76 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 192534.7 (53h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378067
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3383
telemt_upstream_connect_attempt_total 158911
telemt_upstream_connect_success_total 157497
telemt_upstream_connect_fail_total 1414
telemt_upstream_connect_attempts_per_request{bucket="1"} 158911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1414
telemt_me_keepalive_timeout_total 5733
telemt_me_reconnect_attempts_total 198212
telemt_me_reconnect_success_total 42808
telemt_me_reader_eof_total 48771
telemt_me_idle_close_by_peer_total 48771
telemt_me_route_drop_no_conn_total 130609
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251287
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
telemt_me_writer_removed_unexpected_total 48083
telemt_me_refill_failed_total 4848
telemt_me_writer_restored_same_endpoint_total 42790
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5275
telemt_user_connections_total{user="hello"} 356180
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 3629554651 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 114027181498 (106.20 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 192498.5 (53h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434861
telemt_connections_bad_total 3338
telemt_handshake_timeouts_total 36810
telemt_upstream_connect_attempt_total 51670
telemt_upstream_connect_success_total 51661
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4358
telemt_me_reconnect_attempts_total 43299
telemt_me_reconnect_success_total 41975
telemt_me_reader_eof_total 45045
telemt_me_idle_close_by_peer_total 45045
telemt_me_route_drop_no_conn_total 159769
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379041
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
telemt_me_writer_removed_unexpected_total 42474
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41954
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 378775
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 16276753894 (15.16 GB)
telemt_user_octets_to_client{user="hello"} 169201533255 (157.58 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 192474.2 (53h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555576
telemt_connections_bad_total 16788
telemt_handshake_timeouts_total 5357
telemt_upstream_connect_attempt_total 81721
telemt_upstream_connect_success_total 70984
telemt_upstream_connect_fail_total 10737
telemt_upstream_connect_attempts_per_request{bucket="1"} 81721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10737
telemt_me_keepalive_timeout_total 5882
telemt_me_reconnect_attempts_total 162002
telemt_me_reconnect_success_total 42365
telemt_me_reader_eof_total 47436
telemt_me_idle_close_by_peer_total 47428
telemt_me_route_drop_no_conn_total 200582
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477083
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46586
telemt_me_refill_failed_total 3730
telemt_me_writer_restored_same_endpoint_total 42355
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4221
telemt_user_connections_total{user="hello"} 495941
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 10419472323 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 204476193776 (190.43 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 142645.5 (39h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243761
telemt_connections_bad_total 38972
telemt_handshake_timeouts_total 2242
telemt_upstream_connect_attempt_total 50079
telemt_upstream_connect_success_total 49570
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 50079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 3163
telemt_me_reconnect_attempts_total 59831
telemt_me_reconnect_success_total 37573
telemt_me_reader_eof_total 40291
telemt_me_idle_close_by_peer_total 40291
telemt_me_route_drop_no_conn_total 74556
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38617
telemt_me_refill_failed_total 691
telemt_me_writer_restored_same_endpoint_total 37555
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 195803
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2812785025 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 89468142575 (83.32 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 192430.1 (53h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127226
telemt_connections_bad_total 38123
telemt_handshake_timeouts_total 27467
telemt_upstream_connect_attempt_total 40066
telemt_upstream_connect_success_total 39857
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 40066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 5241
telemt_me_reconnect_attempts_total 35042
telemt_me_reconnect_success_total 30342
telemt_me_reader_eof_total 32522
telemt_me_idle_close_by_peer_total 32519
telemt_me_route_drop_no_conn_total 531431
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045479
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
telemt_me_writer_removed_unexpected_total 30872
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30335
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 1018099
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 21872020208 (20.37 GB)
telemt_user_octets_to_client{user="hello"} 516523597016 (481.05 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 63
```