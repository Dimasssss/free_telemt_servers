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

# Server Metrics 2026-03-13 11:08:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 99287.5 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398090
telemt_connections_bad_total 3195
telemt_handshake_timeouts_total 8138
telemt_upstream_connect_attempt_total 25105
telemt_upstream_connect_success_total 24988
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 25105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1833
telemt_me_reconnect_attempts_total 23516
telemt_me_reconnect_success_total 19994
telemt_me_reader_eof_total 21364
telemt_me_idle_close_by_peer_total 21363
telemt_me_route_drop_no_conn_total 126668
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1113
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 20313
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19978
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 343603
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 6154023060 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 150166943136 (139.85 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 99180.3 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182129
telemt_connections_bad_total 1606
telemt_handshake_timeouts_total 1385
telemt_upstream_connect_attempt_total 47922
telemt_upstream_connect_success_total 47245
telemt_upstream_connect_fail_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 47922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 677
telemt_me_keepalive_timeout_total 803
telemt_me_reconnect_attempts_total 89263
telemt_me_reconnect_success_total 25773
telemt_me_reader_eof_total 28514
telemt_me_idle_close_by_peer_total 28514
telemt_me_route_drop_no_conn_total 77549
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 21
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
telemt_me_writer_removed_unexpected_total 27979
telemt_me_refill_failed_total 1980
telemt_me_writer_restored_same_endpoint_total 25756
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2206
telemt_user_connections_total{user="hello"} 171604
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1774305012 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 57303018799 (53.37 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 99144.0 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222465
telemt_connections_bad_total 2052
telemt_handshake_timeouts_total 5089
telemt_upstream_connect_attempt_total 26852
telemt_upstream_connect_success_total 26849
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 23026
telemt_me_reconnect_success_total 21825
telemt_me_reader_eof_total 23384
telemt_me_idle_close_by_peer_total 23384
telemt_me_route_drop_no_conn_total 82945
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207153
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 22063
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21805
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 207072
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 9253614048 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 91487297808 (85.20 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 99119.5 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311834
telemt_connections_bad_total 13696
telemt_handshake_timeouts_total 2278
telemt_upstream_connect_attempt_total 39242
telemt_upstream_connect_success_total 29200
telemt_upstream_connect_fail_total 10042
telemt_upstream_connect_attempts_per_request{bucket="1"} 39242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10042
telemt_me_keepalive_timeout_total 3447
telemt_me_reconnect_attempts_total 86075
telemt_me_reconnect_success_total 21374
telemt_me_reader_eof_total 24043
telemt_me_idle_close_by_peer_total 24036
telemt_me_route_drop_no_conn_total 113022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268159
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 971
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23664
telemt_me_refill_failed_total 2017
telemt_me_writer_restored_same_endpoint_total 21364
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2290
telemt_user_connections_total{user="hello"} 270880
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 5721465542 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 100672882549 (93.76 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49291.1 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68688
telemt_connections_bad_total 9825
telemt_handshake_timeouts_total 740
telemt_upstream_connect_attempt_total 18433
telemt_upstream_connect_success_total 18265
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 18433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 443
telemt_me_reconnect_attempts_total 20477
telemt_me_reconnect_success_total 14630
telemt_me_reader_eof_total 15616
telemt_me_idle_close_by_peer_total 15616
telemt_me_route_drop_no_conn_total 21394
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14943
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 14612
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 55958
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 497491009 (474.44 MB)
telemt_user_octets_to_client{user="hello"} 15261234960 (14.21 GB)
telemt_user_msgs_from_client{user="hello"} 10578
telemt_user_msgs_to_client{user="hello"} 55231
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 99076.2 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551607
telemt_connections_bad_total 14519
telemt_handshake_timeouts_total 10406
telemt_upstream_connect_attempt_total 21099
telemt_upstream_connect_success_total 20989
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 21099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 1636
telemt_me_reconnect_attempts_total 20664
telemt_me_reconnect_success_total 16046
telemt_me_reader_eof_total 17226
telemt_me_idle_close_by_peer_total 17223
telemt_me_route_drop_no_conn_total 278450
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534382
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16402
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16039
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 507460
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 9221767936 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 278161013248 (259.06 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 63
```