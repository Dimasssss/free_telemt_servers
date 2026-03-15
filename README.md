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

# Server Metrics 2026-03-15 15:49:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 63297.3 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288677
telemt_connections_bad_total 2783
telemt_handshake_timeouts_total 8884
telemt_upstream_connect_attempt_total 15810
telemt_upstream_connect_success_total 15727
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15934
telemt_me_reconnect_success_total 12548
telemt_me_reader_eof_total 13369
telemt_me_idle_close_by_peer_total 13369
telemt_me_route_drop_no_conn_total 448484
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326608
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1757
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12786
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12514
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 265710
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 5718233384 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 223246096704 (207.91 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 63304.4 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110133
telemt_connections_bad_total 2809
telemt_handshake_timeouts_total 10534
telemt_upstream_connect_attempt_total 17437
telemt_upstream_connect_success_total 17437
telemt_upstream_connect_attempts_per_request{bucket="1"} 17437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16575
telemt_me_reconnect_success_total 14216
telemt_me_reader_eof_total 15199
telemt_me_idle_close_by_peer_total 15199
telemt_me_route_drop_no_conn_total 45410
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93495
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14455
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14200
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 93479
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 1850566888 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 47607404940 (44.34 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 63296.5 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117792
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 3009
telemt_upstream_connect_attempt_total 18691
telemt_upstream_connect_success_total 18683
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22798
telemt_me_reconnect_success_total 15449
telemt_me_reader_eof_total 16587
telemt_me_idle_close_by_peer_total 16587
telemt_me_route_drop_no_conn_total 45565
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102200
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15822
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15441
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 102098
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 10366833848 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 59064591564 (55.01 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 63296.0 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156580
telemt_connections_bad_total 879
telemt_handshake_timeouts_total 968
telemt_upstream_connect_attempt_total 15273
telemt_upstream_connect_success_total 15265
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12160
telemt_me_reconnect_success_total 12085
telemt_me_reader_eof_total 12849
telemt_me_idle_close_by_peer_total 12849
telemt_me_route_drop_no_conn_total 61088
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143816
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12227
telemt_me_writer_restored_same_endpoint_total 12074
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 143729
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 2777854228 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 68052273904 (63.38 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 38367.5 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93723
telemt_connections_bad_total 22305
telemt_handshake_timeouts_total 2149
telemt_upstream_connect_attempt_total 11913
telemt_upstream_connect_success_total 11842
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104172
telemt_me_reconnect_success_total 9735
telemt_me_reader_eof_total 10187
telemt_me_idle_close_by_peer_total 10187
telemt_me_route_drop_no_conn_total 31978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67089
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9774
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9631
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 67225
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 920053361 (877.43 MB)
telemt_user_octets_to_client{user="hello"} 28011290863 (26.09 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 63296.1 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395399
telemt_connections_bad_total 50367
telemt_handshake_timeouts_total 3356
telemt_upstream_connect_attempt_total 13604
telemt_upstream_connect_success_total 13523
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 13604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11613
telemt_me_reconnect_success_total 10317
telemt_me_reader_eof_total 10973
telemt_me_idle_close_by_peer_total 10973
telemt_me_route_drop_no_conn_total 222732
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348884
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10459
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10290
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 327468
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 8311625520 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 172011979028 (160.20 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 78
```