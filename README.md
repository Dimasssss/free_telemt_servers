# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 21:21:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87328.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3200693
telemt_connections_bad_total 232927
telemt_connections_current 939
telemt_connections_me_current 939
telemt_handshake_timeouts_total 102455
telemt_upstream_connect_attempt_total 31985
telemt_upstream_connect_success_total 31984
telemt_upstream_connect_attempts_per_request{bucket="1"} 31984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1287
telemt_me_reconnect_success_total 534
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 2837074
telemt_me_route_drop_channel_closed_total 1139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2695413
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 589
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 675
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 6
telemt_desync_total 11633
telemt_desync_full_logged_total 3648
telemt_desync_suppressed_total 7985
telemt_desync_frames_bucket_total{bucket="1_2"} 3148
telemt_desync_frames_bucket_total{bucket="3_10"} 4256
telemt_desync_frames_bucket_total{bucket="gt_10"} 4229
telemt_pool_swap_total 96
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 29239
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26246
telemt_me_writer_teardown_success_total{mode="normal"} 29473
telemt_me_writer_teardown_noop_total 29250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58723
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.600633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58723
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2685481
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 39153273352 (36.46 GB)
telemt_user_octets_to_client{user="hello"} 724522121436 (674.76 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 100694.8 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3899310
telemt_connections_bad_total 345624
telemt_connections_current 528
telemt_connections_me_current 528
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99225
telemt_upstream_connect_attempt_total 60337
telemt_upstream_connect_success_total 59603
telemt_upstream_connect_fail_total 648
telemt_upstream_connect_attempts_per_request{bucket="1"} 60251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 648
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6912
telemt_me_reconnect_success_total 2699
telemt_me_reader_eof_total 2648
telemt_me_idle_close_by_peer_total 2648
telemt_me_route_drop_no_conn_total 3624488
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3108389
telemt_me_endpoint_quarantine_total 760
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 776
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 12597
telemt_desync_full_logged_total 7055
telemt_desync_suppressed_total 5542
telemt_desync_frames_bucket_total{bucket="1_2"} 2844
telemt_desync_frames_bucket_total{bucket="3_10"} 4946
telemt_desync_frames_bucket_total{bucket="gt_10"} 4807
telemt_pool_swap_total 94
telemt_pool_force_close_total 2858
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 40085
telemt_me_writer_removed_unexpected_total 2589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4879
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2431
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37227
telemt_me_writer_teardown_success_total{mode="normal"} 42696
telemt_me_writer_teardown_noop_total 40086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.372478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 2378
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 3119067
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 40925685503 (38.12 GB)
telemt_user_octets_to_client{user="hello"} 761224873854 (708.95 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 175554.6 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16081279
telemt_connections_bad_total 1558358
telemt_connections_current 1462
telemt_connections_me_current 1462
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394726
telemt_upstream_connect_attempt_total 77832
telemt_upstream_connect_success_total 77732
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2842
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1420
telemt_me_route_drop_no_conn_total 14011951
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12819899
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 18
telemt_desync_total 52940
telemt_desync_full_logged_total 16714
telemt_desync_suppressed_total 36226
telemt_desync_frames_bucket_total{bucket="1_2"} 11771
telemt_desync_frames_bucket_total{bucket="3_10"} 20624
telemt_desync_frames_bucket_total{bucket="gt_10"} 20545
telemt_pool_swap_total 189
telemt_pool_force_close_total 6356
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1024
telemt_me_draining_writers_reap_progress_total 57796
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51440
telemt_me_writer_teardown_success_total{mode="normal"} 58447
telemt_me_writer_teardown_noop_total 57847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116294
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 314.759476
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116294
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1024
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1276
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12820225
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 188436465429 (175.50 GB)
telemt_user_octets_to_client{user="hello"} 3435279294739 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 175556.1 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11662005
telemt_connections_bad_total 1177647
telemt_connections_current 1051
telemt_connections_me_current 1051
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343460
telemt_upstream_connect_attempt_total 92374
telemt_upstream_connect_success_total 91070
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4277
telemt_me_reconnect_success_total 1785
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1644
telemt_me_route_drop_no_conn_total 4529320
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8686192
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 18
telemt_desync_total 38409
telemt_desync_full_logged_total 12921
telemt_desync_suppressed_total 25488
telemt_desync_frames_bucket_total{bucket="1_2"} 9486
telemt_desync_frames_bucket_total{bucket="3_10"} 14778
telemt_desync_frames_bucket_total{bucket="gt_10"} 14145
telemt_pool_swap_total 186
telemt_pool_force_close_total 5729
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 56215
telemt_me_writer_removed_unexpected_total 1681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52543
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50486
telemt_me_writer_teardown_success_total{mode="normal"} 57745
telemt_me_writer_teardown_noop_total 56240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113985
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.155790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113985
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1518
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8624127
telemt_user_connections_current{user="hello"} 1051
telemt_user_octets_from_client{user="hello"} 216645922048 (201.77 GB)
telemt_user_octets_to_client{user="hello"} 3904419370899 (3.55 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 175521.1 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10910590
telemt_connections_bad_total 947082
telemt_connections_current 771
telemt_connections_me_current 771
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344604
telemt_upstream_connect_attempt_total 75977
telemt_upstream_connect_success_total 74603
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 74800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5363
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 5309301
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8256724
telemt_me_endpoint_quarantine_total 1204
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1283
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 37827
telemt_desync_full_logged_total 12532
telemt_desync_suppressed_total 25295
telemt_desync_frames_bucket_total{bucket="1_2"} 9556
telemt_desync_frames_bucket_total{bucket="3_10"} 14469
telemt_desync_frames_bucket_total{bucket="gt_10"} 13802
telemt_pool_swap_total 183
telemt_pool_force_close_total 5667
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 56365
telemt_me_writer_removed_unexpected_total 2067
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50698
telemt_me_writer_teardown_success_total{mode="normal"} 58356
telemt_me_writer_teardown_noop_total 56436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.207329
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8248755
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 191760930973 (178.59 GB)
telemt_user_octets_to_client{user="hello"} 3431831595565 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45800.2 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10981949
telemt_connections_bad_total 666475
telemt_connections_current 1462
telemt_connections_me_current 1462
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 244083
telemt_upstream_connect_attempt_total 50042
telemt_upstream_connect_success_total 47517
telemt_upstream_connect_fail_total 1730
telemt_upstream_connect_attempts_per_request{bucket="1"} 49247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5984
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1730
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6970
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 25241467
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9119387
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 361
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 15341
telemt_desync_full_logged_total 4078
telemt_desync_suppressed_total 11263
telemt_desync_frames_bucket_total{bucket="1_2"} 2897
telemt_desync_frames_bucket_total{bucket="3_10"} 6228
telemt_desync_frames_bucket_total{bucket="gt_10"} 6216
telemt_pool_swap_total 46
telemt_pool_force_close_total 1638
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 446
telemt_me_draining_writers_reap_progress_total 13279
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12169
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1332
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11641
telemt_me_writer_teardown_success_total{mode="normal"} 14141
telemt_me_writer_teardown_noop_total 13298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.099706
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 446
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 663
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9144141
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 84924722776 (79.09 GB)
telemt_user_octets_to_client{user="hello"} 538812504762 (501.81 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 175526.8 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10815753
telemt_connections_bad_total 911639
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237643
telemt_upstream_connect_attempt_total 104888
telemt_upstream_connect_success_total 103789
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 104725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72457
telemt_me_reconnect_success_total 2860
telemt_me_reader_eof_total 2555
telemt_me_idle_close_by_peer_total 2553
telemt_me_route_drop_no_conn_total 5228270
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8548332
telemt_me_endpoint_quarantine_total 1155
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1311
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 1
telemt_desync_total 45585
telemt_desync_full_logged_total 15558
telemt_desync_suppressed_total 30027
telemt_desync_frames_bucket_total{bucket="1_2"} 9248
telemt_desync_frames_bucket_total{bucket="3_10"} 17457
telemt_desync_frames_bucket_total{bucket="gt_10"} 18880
telemt_pool_swap_total 179
telemt_pool_force_close_total 5346
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 60223
telemt_me_writer_removed_unexpected_total 2590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56491
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4616
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54877
telemt_me_writer_teardown_success_total{mode="normal"} 62842
telemt_me_writer_teardown_noop_total 60224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.116615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2409
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8551467
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 193228059241 (179.96 GB)
telemt_user_octets_to_client{user="hello"} 3259639078700 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 112363.0 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11431708
telemt_connections_bad_total 457097
telemt_connections_current 954
telemt_connections_me_current 954
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4684957
telemt_upstream_connect_attempt_total 53058
telemt_upstream_connect_success_total 52663
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 53048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48656
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1357
telemt_me_route_drop_no_conn_total 4060860
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5514778
telemt_me_endpoint_quarantine_total 725
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 848
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30963
telemt_desync_full_logged_total 10528
telemt_desync_suppressed_total 20435
telemt_desync_frames_bucket_total{bucket="1_2"} 6152
telemt_desync_frames_bucket_total{bucket="3_10"} 12250
telemt_desync_frames_bucket_total{bucket="gt_10"} 12561
telemt_pool_swap_total 118
telemt_pool_force_close_total 3591
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 39274
telemt_me_writer_removed_unexpected_total 1416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35683
telemt_me_writer_teardown_success_total{mode="normal"} 40726
telemt_me_writer_teardown_noop_total 39281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.615183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1507
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5507475
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 118066253216 (109.96 GB)
telemt_user_octets_to_client{user="hello"} 2113117263246 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 93333.7 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1413848
telemt_connections_bad_total 35120
telemt_connections_current 805
telemt_connections_me_current 805
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26337
telemt_upstream_connect_attempt_total 43777
telemt_upstream_connect_success_total 43640
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 43750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 751
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2048
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 491857
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1254544
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 769
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 7754
telemt_desync_full_logged_total 2370
telemt_desync_suppressed_total 5384
telemt_desync_frames_bucket_total{bucket="1_2"} 1830
telemt_desync_frames_bucket_total{bucket="3_10"} 2994
telemt_desync_frames_bucket_total{bucket="gt_10"} 2930
telemt_pool_swap_total 100
telemt_pool_force_close_total 2603
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36555
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2889
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34484
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33952
telemt_me_writer_teardown_success_total{mode="normal"} 37373
telemt_me_writer_teardown_noop_total 36559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73932
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.829154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73932
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1250527
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 24370044853 (22.70 GB)
telemt_user_octets_to_client{user="hello"} 528922790775 (492.60 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 175531.3 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13149348
telemt_connections_bad_total 1555160
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_handshake_timeouts_total 377272
telemt_upstream_connect_attempt_total 66692
telemt_upstream_connect_success_total 66358
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 66556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2586
telemt_me_reconnect_success_total 1362
telemt_me_reader_eof_total 1330
telemt_me_idle_close_by_peer_total 1330
telemt_me_route_drop_no_conn_total 4458948
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9939840
telemt_me_endpoint_quarantine_total 1190
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 3
telemt_desync_total 41455
telemt_desync_full_logged_total 13519
telemt_desync_suppressed_total 27936
telemt_desync_frames_bucket_total{bucket="1_2"} 9971
telemt_desync_frames_bucket_total{bucket="3_10"} 15265
telemt_desync_frames_bucket_total{bucket="gt_10"} 16219
telemt_pool_swap_total 194
telemt_pool_force_close_total 5313
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 60132
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4880
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54819
telemt_me_writer_teardown_success_total{mode="normal"} 61452
telemt_me_writer_teardown_noop_total 60134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.537237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1193
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9906723
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 193535431196 (180.24 GB)
telemt_user_octets_to_client{user="hello"} 4382735754232 (3.99 TB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 175528.0 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11427724
telemt_connections_bad_total 1293693
telemt_connections_current 996
telemt_connections_me_current 996
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 301235
telemt_upstream_connect_attempt_total 93116
telemt_upstream_connect_success_total 92280
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 92909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9975
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 2244
telemt_me_idle_close_by_peer_total 2243
telemt_me_seq_mismatch_total 81
telemt_me_route_drop_no_conn_total 5618498
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8840233
telemt_me_endpoint_quarantine_total 1341
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 40845
telemt_desync_full_logged_total 13115
telemt_desync_suppressed_total 27730
telemt_desync_frames_bucket_total{bucket="1_2"} 10396
telemt_desync_frames_bucket_total{bucket="3_10"} 15078
telemt_desync_frames_bucket_total{bucket="gt_10"} 15371
telemt_pool_swap_total 184
telemt_pool_force_close_total 5111
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59871
telemt_me_writer_removed_unexpected_total 2276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4640
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54760
telemt_me_writer_teardown_success_total{mode="normal"} 62225
telemt_me_writer_teardown_noop_total 59876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.253000
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 112
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8845704
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 156365055049 (145.63 GB)
telemt_user_octets_to_client{user="hello"} 3436956913671 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 122
```