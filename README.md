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

# Server Metrics 2026-03-22 00:38:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 12737.4 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191508
telemt_connections_bad_total 13104
telemt_connections_current 613
telemt_connections_me_current 613
telemt_handshake_timeouts_total 10907
telemt_upstream_connect_attempt_total 5249
telemt_upstream_connect_success_total 5248
telemt_upstream_connect_attempts_per_request{bucket="1"} 5248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 176
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 37598
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156216
telemt_me_endpoint_quarantine_total 93
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 43
telemt_desync_total 1167
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 839
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 14
telemt_pool_force_close_total 351
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 4681
telemt_me_writer_removed_unexpected_total 85
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4330
telemt_me_writer_teardown_success_total{mode="normal"} 4754
telemt_me_writer_teardown_noop_total 4682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.687434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 80
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 155976
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 1780174484 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 53832291636 (50.14 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 26103.2 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699596
telemt_connections_bad_total 40277
telemt_connections_current 693
telemt_connections_me_current 693
telemt_handshake_timeouts_total 26541
telemt_upstream_connect_attempt_total 11251
telemt_upstream_connect_success_total 11058
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 11232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_reconnect_attempts_total 995
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 330159
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565540
telemt_me_endpoint_quarantine_total 237
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 2461
telemt_desync_full_logged_total 1416
telemt_desync_suppressed_total 1045
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 921
telemt_desync_frames_bucket_total{bucket="gt_10"} 1014
telemt_pool_swap_total 28
telemt_pool_force_close_total 772
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 9922
telemt_me_writer_removed_unexpected_total 271
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9338
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9150
telemt_me_writer_teardown_success_total{mode="normal"} 10197
telemt_me_writer_teardown_noop_total 9922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.399200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 564703
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 9367391704 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 199188108432 (185.51 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 100963.0 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7519498
telemt_connections_bad_total 607559
telemt_connections_current 1701
telemt_connections_me_current 1701
telemt_handshake_timeouts_total 244869
telemt_upstream_connect_attempt_total 36771
telemt_upstream_connect_success_total 36699
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1521
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 770
telemt_me_idle_close_by_peer_total 770
telemt_me_route_drop_no_conn_total 4508251
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6120686
telemt_me_endpoint_quarantine_total 641
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 749
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 45
telemt_desync_total 25958
telemt_desync_full_logged_total 8589
telemt_desync_suppressed_total 17369
telemt_desync_frames_bucket_total{bucket="1_2"} 5584
telemt_desync_frames_bucket_total{bucket="3_10"} 10122
telemt_desync_frames_bucket_total{bucket="gt_10"} 10252
telemt_pool_swap_total 109
telemt_pool_force_close_total 3635
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 577
telemt_me_draining_writers_reap_progress_total 33502
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29867
telemt_me_writer_teardown_success_total{mode="normal"} 33801
telemt_me_writer_teardown_noop_total 33546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.850631
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 577
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 676
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6113010
telemt_user_connections_current{user="hello"} 1701
telemt_user_octets_from_client{user="hello"} 104912684060 (97.71 GB)
telemt_user_octets_to_client{user="hello"} 2018241167920 (1.84 TB)
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 100964.4 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6187651
telemt_connections_bad_total 580546
telemt_connections_current 1467
telemt_connections_me_current 1467
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 204727
telemt_upstream_connect_attempt_total 40946
telemt_upstream_connect_success_total 40563
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 40749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1857
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 2204239
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4636478
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 771
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22189
telemt_desync_full_logged_total 7524
telemt_desync_suppressed_total 14665
telemt_desync_frames_bucket_total{bucket="1_2"} 5346
telemt_desync_frames_bucket_total{bucket="3_10"} 8604
telemt_desync_frames_bucket_total{bucket="gt_10"} 8239
telemt_pool_swap_total 110
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 32214
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30172
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28923
telemt_me_writer_teardown_success_total{mode="normal"} 32925
telemt_me_writer_teardown_noop_total 32220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.041856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4572008
telemt_user_connections_current{user="hello"} 1467
telemt_user_octets_from_client{user="hello"} 138648644893 (129.13 GB)
telemt_user_octets_to_client{user="hello"} 2146372431143 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 100928.5 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6092815
telemt_connections_bad_total 541656
telemt_connections_current 1216
telemt_connections_me_current 1216
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195417
telemt_upstream_connect_attempt_total 47253
telemt_upstream_connect_success_total 46929
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1053
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1843
telemt_me_reconnect_success_total 856
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 2114168
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4544987
telemt_me_endpoint_quarantine_total 692
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 22069
telemt_desync_full_logged_total 7368
telemt_desync_suppressed_total 14701
telemt_desync_frames_bucket_total{bucket="1_2"} 5394
telemt_desync_frames_bucket_total{bucket="3_10"} 8449
telemt_desync_frames_bucket_total{bucket="gt_10"} 8226
telemt_pool_swap_total 109
telemt_pool_force_close_total 3173
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33558
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30385
telemt_me_writer_teardown_success_total{mode="normal"} 34336
telemt_me_writer_teardown_noop_total 33569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.552426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4545905
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 132160648823 (123.08 GB)
telemt_user_octets_to_client{user="hello"} 2079991177791 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 100967.8 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20088754
telemt_connections_bad_total 1511908
telemt_connections_current 2064
telemt_connections_me_current 2064
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 583813
telemt_upstream_connect_attempt_total 190193
telemt_upstream_connect_success_total 172522
telemt_upstream_connect_fail_total 16044
telemt_upstream_connect_attempts_per_request{bucket="1"} 188566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8889
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16044
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64392
telemt_me_reconnect_success_total 2191
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1373
telemt_me_route_drop_no_conn_total 39466510
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16323777
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 124
telemt_me_single_endpoint_outage_exit_total 124
telemt_me_single_endpoint_outage_reconnect_attempt_total 260
telemt_me_single_endpoint_outage_reconnect_success_total 63
telemt_me_single_endpoint_quarantine_bypass_total 260
telemt_me_single_endpoint_shadow_rotate_total 789
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 31526
telemt_desync_full_logged_total 9396
telemt_desync_suppressed_total 22130
telemt_desync_frames_bucket_total{bucket="1_2"} 6853
telemt_desync_frames_bucket_total{bucket="3_10"} 13980
telemt_desync_frames_bucket_total{bucket="gt_10"} 10693
telemt_pool_swap_total 104
telemt_pool_force_close_total 3411
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 765
telemt_me_draining_writers_reap_progress_total 31385
telemt_me_writer_removed_unexpected_total 2033
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27974
telemt_me_writer_teardown_success_total{mode="normal"} 33154
telemt_me_writer_teardown_noop_total 31411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.383980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 765
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1520
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16451423
telemt_user_connections_current{user="hello"} 2064
telemt_user_octets_from_client{user="hello"} 194372152384 (181.02 GB)
telemt_user_octets_to_client{user="hello"} 1144649360106 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 100935.1 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5876347
telemt_connections_bad_total 553039
telemt_connections_current 1475
telemt_connections_me_current 1475
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122129
telemt_upstream_connect_attempt_total 55382
telemt_upstream_connect_success_total 54739
telemt_upstream_connect_fail_total 549
telemt_upstream_connect_attempts_per_request{bucket="1"} 55288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 549
telemt_me_reconnect_attempts_total 69396
telemt_me_reconnect_success_total 1719
telemt_me_reader_eof_total 1498
telemt_me_idle_close_by_peer_total 1497
telemt_me_route_drop_no_conn_total 2366246
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4582222
telemt_me_endpoint_quarantine_total 678
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 755
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 40
telemt_desync_total 23051
telemt_desync_full_logged_total 8083
telemt_desync_suppressed_total 14968
telemt_desync_frames_bucket_total{bucket="1_2"} 4372
telemt_desync_frames_bucket_total{bucket="3_10"} 8928
telemt_desync_frames_bucket_total{bucket="gt_10"} 9751
telemt_pool_swap_total 104
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 34922
telemt_me_writer_removed_unexpected_total 1542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3698
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32791
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31903
telemt_me_writer_teardown_success_total{mode="normal"} 36489
telemt_me_writer_teardown_noop_total 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.994388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 4575273
telemt_user_connections_current{user="hello"} 1475
telemt_user_octets_from_client{user="hello"} 122667035448 (114.24 GB)
telemt_user_octets_to_client{user="hello"} 1870241699358 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37770.9 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3756425
telemt_connections_bad_total 134801
telemt_connections_current 1207
telemt_connections_me_current 1207
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1553236
telemt_upstream_connect_attempt_total 23643
telemt_upstream_connect_success_total 23491
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 23636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 45671
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 1002914
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1823238
telemt_me_endpoint_quarantine_total 273
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10091
telemt_desync_full_logged_total 3463
telemt_desync_suppressed_total 6628
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 3866
telemt_desync_frames_bucket_total{bucket="gt_10"} 4442
telemt_pool_swap_total 40
telemt_pool_force_close_total 1294
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 13014
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12347
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11720
telemt_me_writer_teardown_success_total{mode="normal"} 13695
telemt_me_writer_teardown_noop_total 13016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.218766
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1826980
telemt_user_connections_current{user="hello"} 1207
telemt_user_octets_from_client{user="hello"} 52999023660 (49.36 GB)
telemt_user_octets_to_client{user="hello"} 783191667722 (729.40 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 18742.0 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169338
telemt_connections_bad_total 1415
telemt_connections_current 295
telemt_connections_me_current 295
telemt_handshake_timeouts_total 4701
telemt_upstream_connect_attempt_total 8717
telemt_upstream_connect_success_total 8697
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 181
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 47333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148751
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 45
telemt_desync_total 994
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 20
telemt_pool_force_close_total 459
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7814
telemt_me_writer_removed_unexpected_total 116
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 517
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7416
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7355
telemt_me_writer_teardown_success_total{mode="normal"} 7933
telemt_me_writer_teardown_noop_total 7814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15747
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.821013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15747
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 148465
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2798836548 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 86084690848 (80.17 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 100939.6 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7101436
telemt_connections_bad_total 719730
telemt_connections_current 1536
telemt_connections_me_current 1536
telemt_handshake_timeouts_total 202460
telemt_upstream_connect_attempt_total 38905
telemt_upstream_connect_success_total 38756
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 38868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_reconnect_attempts_total 1519
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 2104352
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5351290
telemt_me_endpoint_quarantine_total 699
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 773
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20704
telemt_desync_full_logged_total 6918
telemt_desync_suppressed_total 13786
telemt_desync_frames_bucket_total{bucket="1_2"} 5036
telemt_desync_frames_bucket_total{bucket="3_10"} 7508
telemt_desync_frames_bucket_total{bucket="gt_10"} 8160
telemt_pool_swap_total 112
telemt_pool_force_close_total 3018
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 35003
telemt_me_writer_removed_unexpected_total 758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32959
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31985
telemt_me_writer_teardown_success_total{mode="normal"} 35779
telemt_me_writer_teardown_noop_total 35005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.579843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5326455
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 108084861908 (100.66 GB)
telemt_user_octets_to_client{user="hello"} 2498819426196 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 738
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 100936.0 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6098805
telemt_connections_bad_total 600491
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168693
telemt_upstream_connect_attempt_total 54736
telemt_upstream_connect_success_total 54320
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5414
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2158397
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4722609
telemt_me_endpoint_quarantine_total 807
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 770
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19469
telemt_desync_full_logged_total 6548
telemt_desync_suppressed_total 12921
telemt_desync_frames_bucket_total{bucket="1_2"} 4883
telemt_desync_frames_bucket_total{bucket="3_10"} 7080
telemt_desync_frames_bucket_total{bucket="gt_10"} 7506
telemt_pool_swap_total 110
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 33638
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31381
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30657
telemt_me_writer_teardown_success_total{mode="normal"} 34683
telemt_me_writer_teardown_noop_total 33642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.955191
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4725826
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 89352878337 (83.22 GB)
telemt_user_octets_to_client{user="hello"} 2026385138708 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 145
```