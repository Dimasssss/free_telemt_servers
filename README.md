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

# Server Metrics 2026-03-22 00:28:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 12124.4 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183845
telemt_connections_bad_total 12377
telemt_connections_current 625
telemt_connections_me_current 625
telemt_handshake_timeouts_total 10245
telemt_upstream_connect_attempt_total 4965
telemt_upstream_connect_success_total 4964
telemt_upstream_connect_attempts_per_request{bucket="1"} 4964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 168
telemt_me_reconnect_success_total 80
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 36678
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150538
telemt_me_endpoint_quarantine_total 84
telemt_me_single_endpoint_shadow_rotate_total 105
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
telemt_me_writers_active_current 45
telemt_desync_total 1080
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 13
telemt_pool_force_close_total 351
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 4450
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4099
telemt_me_writer_teardown_success_total{mode="normal"} 4516
telemt_me_writer_teardown_noop_total 4451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8967
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.673742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8967
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 150325
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 1721180092 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 52130407792 (48.55 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 25493.8 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694237
telemt_connections_bad_total 40189
telemt_connections_current 368
telemt_connections_me_current 368
telemt_handshake_timeouts_total 26335
telemt_upstream_connect_attempt_total 10983
telemt_upstream_connect_success_total 10790
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 10964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_reconnect_attempts_total 988
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 283
telemt_me_idle_close_by_peer_total 283
telemt_me_route_drop_no_conn_total 329337
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560758
telemt_me_endpoint_quarantine_total 237
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 208
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
telemt_me_writers_active_current 43
telemt_desync_total 2445
telemt_desync_full_logged_total 1405
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 1008
telemt_pool_swap_total 28
telemt_pool_force_close_total 772
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 9695
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 851
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9114
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8923
telemt_me_writer_teardown_success_total{mode="normal"} 9965
telemt_me_writer_teardown_noop_total 9695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19660
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.395989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19660
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 559937
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 9285028192 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 196832854776 (183.31 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 100350.5 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7500978
telemt_connections_bad_total 602170
telemt_connections_current 1471
telemt_connections_me_current 1471
telemt_handshake_timeouts_total 244064
telemt_upstream_connect_attempt_total 36522
telemt_upstream_connect_success_total 36450
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1502
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 4506347
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6109699
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 746
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
telemt_me_writers_active_current 43
telemt_desync_total 25912
telemt_desync_full_logged_total 8569
telemt_desync_suppressed_total 17343
telemt_desync_frames_bucket_total{bucket="1_2"} 5575
telemt_desync_frames_bucket_total{bucket="3_10"} 10106
telemt_desync_frames_bucket_total{bucket="gt_10"} 10231
telemt_pool_swap_total 108
telemt_pool_force_close_total 3635
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 577
telemt_me_draining_writers_reap_progress_total 33295
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30777
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29660
telemt_me_writer_teardown_success_total{mode="normal"} 33588
telemt_me_writer_teardown_noop_total 33339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.844164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 577
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 674
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6102028
telemt_user_connections_current{user="hello"} 1471
telemt_user_octets_from_client{user="hello"} 104430400188 (97.26 GB)
telemt_user_octets_to_client{user="hello"} 2011828620584 (1.83 TB)
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 100352.0 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6172890
telemt_connections_bad_total 580177
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 203869
telemt_upstream_connect_attempt_total 40656
telemt_upstream_connect_success_total 40275
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 40460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1852
telemt_me_reconnect_success_total 815
telemt_me_reader_eof_total 788
telemt_me_idle_close_by_peer_total 788
telemt_me_route_drop_no_conn_total 2198508
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4625781
telemt_me_endpoint_quarantine_total 618
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 768
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22168
telemt_desync_full_logged_total 7511
telemt_desync_suppressed_total 14657
telemt_desync_frames_bucket_total{bucket="1_2"} 5340
telemt_desync_frames_bucket_total{bucket="3_10"} 8598
telemt_desync_frames_bucket_total{bucket="gt_10"} 8230
telemt_pool_swap_total 109
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 31962
telemt_me_writer_removed_unexpected_total 770
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29932
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28671
telemt_me_writer_teardown_success_total{mode="normal"} 32667
telemt_me_writer_teardown_noop_total 31968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.037409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4562789
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 138496473725 (128.98 GB)
telemt_user_octets_to_client{user="hello"} 2139078774687 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 100316.1 (27h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6078962
telemt_connections_bad_total 541023
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 194803
telemt_upstream_connect_attempt_total 46960
telemt_upstream_connect_success_total 46641
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20949
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1830
telemt_me_reconnect_success_total 843
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 784
telemt_me_route_drop_no_conn_total 2111998
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4536980
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 752
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 22037
telemt_desync_full_logged_total 7354
telemt_desync_suppressed_total 14683
telemt_desync_frames_bucket_total{bucket="1_2"} 5393
telemt_desync_frames_bucket_total{bucket="3_10"} 8437
telemt_desync_frames_bucket_total{bucket="gt_10"} 8207
telemt_pool_swap_total 108
telemt_pool_force_close_total 3173
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33334
telemt_me_writer_removed_unexpected_total 754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2789
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31308
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30161
telemt_me_writer_teardown_success_total{mode="normal"} 34097
telemt_me_writer_teardown_noop_total 33345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67442
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.548515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67442
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 730
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4537906
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 132054965471 (122.99 GB)
telemt_user_octets_to_client{user="hello"} 2078371216763 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 100355.4 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20063052
telemt_connections_bad_total 1502931
telemt_connections_current 2163
telemt_connections_me_current 2163
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 582082
telemt_upstream_connect_attempt_total 189952
telemt_upstream_connect_success_total 172293
telemt_upstream_connect_fail_total 16039
telemt_upstream_connect_attempts_per_request{bucket="1"} 188332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8887
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16039
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64374
telemt_me_reconnect_success_total 2178
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 39462330
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16309326
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 772
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 784
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
telemt_me_writers_active_current 44
telemt_desync_total 31463
telemt_desync_full_logged_total 9366
telemt_desync_suppressed_total 22097
telemt_desync_frames_bucket_total{bucket="1_2"} 6842
telemt_desync_frames_bucket_total{bucket="3_10"} 13944
telemt_desync_frames_bucket_total{bucket="gt_10"} 10677
telemt_pool_swap_total 103
telemt_pool_force_close_total 3408
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 31213
telemt_me_writer_removed_unexpected_total 2024
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28713
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27805
telemt_me_writer_teardown_success_total{mode="normal"} 32973
telemt_me_writer_teardown_noop_total 31239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.378235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1511
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16437065
telemt_user_connections_current{user="hello"} 2163
telemt_user_octets_from_client{user="hello"} 192405445176 (179.19 GB)
telemt_user_octets_to_client{user="hello"} 1138339426590 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 100322.8 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5866506
telemt_connections_bad_total 552698
telemt_connections_current 1485
telemt_connections_me_current 1485
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 121232
telemt_upstream_connect_attempt_total 55096
telemt_upstream_connect_success_total 54467
telemt_upstream_connect_fail_total 538
telemt_upstream_connect_attempts_per_request{bucket="1"} 55005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 538
telemt_me_reconnect_attempts_total 68176
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1482
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 2364213
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4574144
telemt_me_endpoint_quarantine_total 672
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 23032
telemt_desync_full_logged_total 8077
telemt_desync_suppressed_total 14955
telemt_desync_frames_bucket_total{bucket="1_2"} 4366
telemt_desync_frames_bucket_total{bucket="3_10"} 8920
telemt_desync_frames_bucket_total{bucket="gt_10"} 9746
telemt_pool_swap_total 103
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 34711
telemt_me_writer_removed_unexpected_total 1527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31692
telemt_me_writer_teardown_success_total{mode="normal"} 36262
telemt_me_writer_teardown_noop_total 34712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.992348
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 4122
telemt_me_writer_restored_same_endpoint_total 1435
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4567185
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 122566136928 (114.15 GB)
telemt_user_octets_to_client{user="hello"} 1866673092434 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37158.7 (10h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3741324
telemt_connections_bad_total 132783
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1548978
telemt_upstream_connect_attempt_total 23407
telemt_upstream_connect_success_total 23255
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 23400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 45665
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 576
telemt_me_idle_close_by_peer_total 576
telemt_me_route_drop_no_conn_total 1001341
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1815611
telemt_me_endpoint_quarantine_total 273
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 283
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10047
telemt_desync_full_logged_total 3447
telemt_desync_suppressed_total 6600
telemt_desync_frames_bucket_total{bucket="1_2"} 1775
telemt_desync_frames_bucket_total{bucket="3_10"} 3851
telemt_desync_frames_bucket_total{bucket="gt_10"} 4421
telemt_pool_swap_total 40
telemt_pool_force_close_total 1294
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 122
telemt_me_draining_writers_reap_progress_total 12809
telemt_me_writer_removed_unexpected_total 655
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11515
telemt_me_writer_teardown_success_total{mode="normal"} 13485
telemt_me_writer_teardown_noop_total 12811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.217838
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 122
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1819349
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 52863265008 (49.23 GB)
telemt_user_octets_to_client{user="hello"} 778185020242 (724.74 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 18129.6 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166697
telemt_connections_bad_total 1409
telemt_connections_current 287
telemt_connections_me_current 287
telemt_handshake_timeouts_total 4386
telemt_upstream_connect_attempt_total 8408
telemt_upstream_connect_success_total 8388
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 174
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 46818
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146532
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 986
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 741
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 20
telemt_pool_force_close_total 442
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7520
telemt_me_writer_removed_unexpected_total 110
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 493
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7140
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7078
telemt_me_writer_teardown_success_total{mode="normal"} 7633
telemt_me_writer_teardown_noop_total 7520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15153
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.814908
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15153
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 146246
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2769818972 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 85436926512 (79.57 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 100327.3 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7086243
telemt_connections_bad_total 718402
telemt_connections_current 1580
telemt_connections_me_current 1580
telemt_handshake_timeouts_total 201731
telemt_upstream_connect_attempt_total 38578
telemt_upstream_connect_success_total 38430
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 38540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1509
telemt_me_reconnect_success_total 794
telemt_me_reader_eof_total 776
telemt_me_idle_close_by_peer_total 776
telemt_me_route_drop_no_conn_total 2102497
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5341582
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 771
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20642
telemt_desync_full_logged_total 6895
telemt_desync_suppressed_total 13747
telemt_desync_frames_bucket_total{bucket="1_2"} 5024
telemt_desync_frames_bucket_total{bucket="3_10"} 7487
telemt_desync_frames_bucket_total{bucket="gt_10"} 8131
telemt_pool_swap_total 111
telemt_pool_force_close_total 3018
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 34716
telemt_me_writer_removed_unexpected_total 748
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31698
telemt_me_writer_teardown_success_total{mode="normal"} 35482
telemt_me_writer_teardown_noop_total 34718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70200
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.577337
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70200
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 5316748
telemt_user_connections_current{user="hello"} 1580
telemt_user_octets_from_client{user="hello"} 108029521696 (100.61 GB)
telemt_user_octets_to_client{user="hello"} 2496340213328 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 744
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 100323.9 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6078882
telemt_connections_bad_total 597790
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168402
telemt_upstream_connect_attempt_total 54444
telemt_upstream_connect_success_total 54028
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5411
telemt_me_reconnect_success_total 1102
telemt_me_reader_eof_total 985
telemt_me_idle_close_by_peer_total 985
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2156545
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4712761
telemt_me_endpoint_quarantine_total 799
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 766
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 19424
telemt_desync_full_logged_total 6531
telemt_desync_suppressed_total 12893
telemt_desync_frames_bucket_total{bucket="1_2"} 4878
telemt_desync_frames_bucket_total{bucket="3_10"} 7067
telemt_desync_frames_bucket_total{bucket="gt_10"} 7479
telemt_pool_swap_total 109
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 33383
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3285
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31140
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30402
telemt_me_writer_teardown_success_total{mode="normal"} 34425
telemt_me_writer_teardown_noop_total 33387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.951585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4715977
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 89095159997 (82.98 GB)
telemt_user_octets_to_client{user="hello"} 2022101288460 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 156
```