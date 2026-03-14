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

# Server Metrics 2026-03-14 12:13:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 189585.3 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750083
telemt_connections_bad_total 35484
telemt_handshake_timeouts_total 14451
telemt_upstream_connect_attempt_total 48115
telemt_upstream_connect_success_total 47876
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 48115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6337
telemt_me_reconnect_attempts_total 43821
telemt_me_reconnect_success_total 38053
telemt_me_reader_eof_total 40687
telemt_me_idle_close_by_peer_total 40686
telemt_me_route_drop_no_conn_total 246731
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2734
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 1821
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 1145
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 38643
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38033
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 642927
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 17850095258 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 308505774372 (287.32 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 189478.0 (52h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371280
telemt_connections_bad_total 2848
telemt_handshake_timeouts_total 3341
telemt_upstream_connect_attempt_total 157916
telemt_upstream_connect_success_total 156522
telemt_upstream_connect_fail_total 1394
telemt_upstream_connect_attempts_per_request{bucket="1"} 157916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2521
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1394
telemt_me_keepalive_timeout_total 5712
telemt_me_reconnect_attempts_total 196599
telemt_me_reconnect_success_total 41970
telemt_me_reader_eof_total 47893
telemt_me_idle_close_by_peer_total 47893
telemt_me_route_drop_no_conn_total 128149
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245689
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
telemt_me_writer_removed_unexpected_total 47202
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 41952
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5232
telemt_user_connections_total{user="hello"} 350582
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 3553265947 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 112841407586 (105.09 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 189441.7 (52h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428871
telemt_connections_bad_total 3320
telemt_handshake_timeouts_total 36623
telemt_upstream_connect_attempt_total 50568
telemt_upstream_connect_success_total 50559
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4297
telemt_me_reconnect_attempts_total 42332
telemt_me_reconnect_success_total 41009
telemt_me_reader_eof_total 44048
telemt_me_idle_close_by_peer_total 44048
telemt_me_route_drop_no_conn_total 156933
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373533
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41500
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40988
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 373291
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 16187448370 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 163435069027 (152.21 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 189417.3 (52h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545015
telemt_connections_bad_total 16779
telemt_handshake_timeouts_total 5323
telemt_upstream_connect_attempt_total 81022
telemt_upstream_connect_success_total 70308
telemt_upstream_connect_fail_total 10713
telemt_upstream_connect_attempts_per_request{bucket="1"} 81021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10713
telemt_me_keepalive_timeout_total 5852
telemt_me_reconnect_attempts_total 157493
telemt_me_reconnect_success_total 41825
telemt_me_reader_eof_total 46769
telemt_me_idle_close_by_peer_total 46761
telemt_me_route_drop_no_conn_total 197372
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1535
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 844
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45918
telemt_me_refill_failed_total 3606
telemt_me_writer_restored_same_endpoint_total 41815
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4093
telemt_user_connections_total{user="hello"} 486147
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 10281560047 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 200561840192 (186.79 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 139588.9 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237308
telemt_connections_bad_total 38203
telemt_handshake_timeouts_total 2183
telemt_upstream_connect_attempt_total 49129
telemt_upstream_connect_success_total 48631
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 49129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 3131
telemt_me_reconnect_attempts_total 53700
telemt_me_reconnect_success_total 36786
telemt_me_reader_eof_total 39336
telemt_me_idle_close_by_peer_total 39336
telemt_me_route_drop_no_conn_total 71885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185684
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37662
telemt_me_refill_failed_total 524
telemt_me_writer_restored_same_endpoint_total 36768
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 876
telemt_user_connections_total{user="hello"} 190440
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2764117017 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 87852582943 (81.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 189373.5 (52h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105315
telemt_connections_bad_total 37730
telemt_handshake_timeouts_total 27249
telemt_upstream_connect_attempt_total 39477
telemt_upstream_connect_success_total 39270
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5206
telemt_me_reconnect_attempts_total 34589
telemt_me_reconnect_success_total 29895
telemt_me_reader_eof_total 32056
telemt_me_idle_close_by_peer_total 32053
telemt_me_route_drop_no_conn_total 519668
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025128
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
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 30420
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29888
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 997713
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 21335385396 (19.87 GB)
telemt_user_octets_to_client{user="hello"} 501111225780 (466.70 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 69
```