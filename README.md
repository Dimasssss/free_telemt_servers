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

# Server Metrics 2026-03-22 21:52:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 89163.4 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3256260
telemt_connections_bad_total 239438
telemt_connections_current 910
telemt_connections_me_current 910
telemt_handshake_timeouts_total 103754
telemt_upstream_connect_attempt_total 32677
telemt_upstream_connect_success_total 32676
telemt_upstream_connect_attempts_per_request{bucket="1"} 32676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 379
telemt_me_reconnect_attempts_total 1314
telemt_me_reconnect_success_total 544
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 2866851
telemt_me_route_drop_channel_closed_total 1202
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2742126
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 599
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 26
telemt_desync_total 11816
telemt_desync_full_logged_total 3705
telemt_desync_suppressed_total 8111
telemt_desync_frames_bucket_total{bucket="1_2"} 3205
telemt_desync_frames_bucket_total{bucket="3_10"} 4313
telemt_desync_frames_bucket_total{bucket="gt_10"} 4298
telemt_pool_swap_total 98
telemt_pool_force_close_total 3048
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 29854
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26806
telemt_me_writer_teardown_success_total{mode="normal"} 30090
telemt_me_writer_teardown_noop_total 29865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 352.744407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2731751
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 39440023392 (36.73 GB)
telemt_user_octets_to_client{user="hello"} 738416119316 (687.70 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 102529.8 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3920211
telemt_connections_bad_total 349435
telemt_connections_current 791
telemt_connections_me_current 791
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99489
telemt_upstream_connect_attempt_total 61500
telemt_upstream_connect_success_total 60757
telemt_upstream_connect_fail_total 657
telemt_upstream_connect_attempts_per_request{bucket="1"} 61414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 657
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7033
telemt_me_reconnect_success_total 2770
telemt_me_reader_eof_total 2719
telemt_me_idle_close_by_peer_total 2719
telemt_me_route_drop_no_conn_total 3629353
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3123631
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 792
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
telemt_me_writers_active_current 93
telemt_desync_total 12690
telemt_desync_full_logged_total 7112
telemt_desync_suppressed_total 5578
telemt_desync_frames_bucket_total{bucket="1_2"} 2865
telemt_desync_frames_bucket_total{bucket="3_10"} 4983
telemt_desync_frames_bucket_total{bucket="gt_10"} 4842
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41073
telemt_me_writer_removed_unexpected_total 2659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38194
telemt_me_writer_teardown_success_total{mode="normal"} 43755
telemt_me_writer_teardown_noop_total 41074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84829
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.396503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84829
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 3134294
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 41700640643 (38.84 GB)
telemt_user_octets_to_client{user="hello"} 770639356154 (717.71 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 177389.5 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16133357
telemt_connections_bad_total 1576034
telemt_connections_current 1269
telemt_connections_me_current 1269
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395418
telemt_upstream_connect_attempt_total 78685
telemt_upstream_connect_success_total 78585
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2852
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 1430
telemt_me_idle_close_by_peer_total 1428
telemt_me_route_drop_no_conn_total 14020545
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12851676
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1322
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
telemt_me_writers_warm_current 40
telemt_desync_total 53084
telemt_desync_full_logged_total 16782
telemt_desync_suppressed_total 36302
telemt_desync_frames_bucket_total{bucket="1_2"} 11791
telemt_desync_frames_bucket_total{bucket="3_10"} 20672
telemt_desync_frames_bucket_total{bucket="gt_10"} 20621
telemt_pool_swap_total 191
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1037
telemt_me_draining_writers_reap_progress_total 58577
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54109
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52161
telemt_me_writer_teardown_success_total{mode="normal"} 59226
telemt_me_writer_teardown_noop_total 58630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117856
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.901286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117856
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1037
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12851973
telemt_user_connections_current{user="hello"} 1269
telemt_user_octets_from_client{user="hello"} 189308132177 (176.31 GB)
telemt_user_octets_to_client{user="hello"} 3447883266527 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 177391.0 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11705626
telemt_connections_bad_total 1192669
telemt_connections_current 872
telemt_connections_me_current 872
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343619
telemt_upstream_connect_attempt_total 93151
telemt_upstream_connect_success_total 91843
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3792
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4286
telemt_me_reconnect_success_total 1793
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1653
telemt_me_route_drop_no_conn_total 4535498
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8712559
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_warm_current 34
telemt_desync_total 38494
telemt_desync_full_logged_total 12948
telemt_desync_suppressed_total 25546
telemt_desync_frames_bucket_total{bucket="1_2"} 9504
telemt_desync_frames_bucket_total{bucket="3_10"} 14798
telemt_desync_frames_bucket_total{bucket="gt_10"} 14192
telemt_pool_swap_total 188
telemt_pool_force_close_total 5787
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56918
telemt_me_writer_removed_unexpected_total 1689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53210
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51131
telemt_me_writer_teardown_success_total{mode="normal"} 58457
telemt_me_writer_teardown_noop_total 56943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.223813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1526
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8650438
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 216862303092 (201.97 GB)
telemt_user_octets_to_client{user="hello"} 3919228162011 (3.56 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 177355.9 (49h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10933997
telemt_connections_bad_total 950215
telemt_connections_current 686
telemt_connections_me_current 686
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344717
telemt_upstream_connect_attempt_total 76833
telemt_upstream_connect_success_total 75395
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 75594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5400
telemt_me_reconnect_success_total 2202
telemt_me_reader_eof_total 1938
telemt_me_idle_close_by_peer_total 1937
telemt_me_route_drop_no_conn_total 5315533
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8274875
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_warm_current 4
telemt_desync_total 37845
telemt_desync_full_logged_total 12539
telemt_desync_suppressed_total 25306
telemt_desync_frames_bucket_total{bucket="1_2"} 9563
telemt_desync_frames_bucket_total{bucket="3_10"} 14474
telemt_desync_frames_bucket_total{bucket="gt_10"} 13808
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 57038
telemt_me_writer_removed_unexpected_total 2088
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51316
telemt_me_writer_teardown_success_total{mode="normal"} 59052
telemt_me_writer_teardown_noop_total 57109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116161
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.231139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116161
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1902
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8266884
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 191899799205 (178.72 GB)
telemt_user_octets_to_client{user="hello"} 3439554003537 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47635.2 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11030130
telemt_connections_bad_total 666857
telemt_connections_current 1262
telemt_connections_me_current 1262
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 248150
telemt_upstream_connect_attempt_total 50812
telemt_upstream_connect_success_total 48269
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 50004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7011
telemt_me_reconnect_success_total 1032
telemt_me_reader_eof_total 642
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 25253192
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9160709
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 375
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
telemt_me_writers_active_current 43
telemt_desync_total 15688
telemt_desync_full_logged_total 4150
telemt_desync_suppressed_total 11538
telemt_desync_frames_bucket_total{bucket="1_2"} 3004
telemt_desync_frames_bucket_total{bucket="3_10"} 6342
telemt_desync_frames_bucket_total{bucket="gt_10"} 6342
telemt_pool_swap_total 48
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 450
telemt_me_draining_writers_reap_progress_total 13960
telemt_me_writer_removed_unexpected_total 919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2023
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12814
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12273
telemt_me_writer_teardown_success_total{mode="normal"} 14837
telemt_me_writer_teardown_noop_total 13979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28816
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.147749
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28816
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 450
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9185416
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 85340092828 (79.48 GB)
telemt_user_octets_to_client{user="hello"} 554825637966 (516.72 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 177361.7 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10848882
telemt_connections_bad_total 914202
telemt_connections_current 1225
telemt_connections_me_current 1225
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238851
telemt_upstream_connect_attempt_total 105998
telemt_upstream_connect_success_total 104891
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 105832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72601
telemt_me_reconnect_success_total 2933
telemt_me_reader_eof_total 2629
telemt_me_idle_close_by_peer_total 2627
telemt_me_route_drop_no_conn_total 5236547
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8573986
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 92
telemt_me_writers_warm_current 22
telemt_desync_total 45780
telemt_desync_full_logged_total 15652
telemt_desync_suppressed_total 30128
telemt_desync_frames_bucket_total{bucket="1_2"} 9281
telemt_desync_frames_bucket_total{bucket="3_10"} 17519
telemt_desync_frames_bucket_total{bucket="gt_10"} 18980
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 61148
telemt_me_writer_removed_unexpected_total 2664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57389
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55777
telemt_me_writer_teardown_success_total{mode="normal"} 63841
telemt_me_writer_teardown_noop_total 61149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124990
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.143952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124990
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2479
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8577096
telemt_user_connections_current{user="hello"} 1225
telemt_user_octets_from_client{user="hello"} 193566773025 (180.27 GB)
telemt_user_octets_to_client{user="hello"} 3272852263004 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 519
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 114198.0 (31h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11486448
telemt_connections_bad_total 459645
telemt_connections_current 616
telemt_connections_me_current 616
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4706809
telemt_upstream_connect_attempt_total 53937
telemt_upstream_connect_success_total 53541
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 53927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 48664
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 4067509
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5535747
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 863
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31094
telemt_desync_full_logged_total 10592
telemt_desync_suppressed_total 20502
telemt_desync_frames_bucket_total{bucket="1_2"} 6170
telemt_desync_frames_bucket_total{bucket="3_10"} 12285
telemt_desync_frames_bucket_total{bucket="gt_10"} 12639
telemt_pool_swap_total 120
telemt_pool_force_close_total 3641
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 40081
telemt_me_writer_removed_unexpected_total 1422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36440
telemt_me_writer_teardown_success_total{mode="normal"} 41540
telemt_me_writer_teardown_noop_total 40088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.623837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1513
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5528409
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 118291069576 (110.17 GB)
telemt_user_octets_to_client{user="hello"} 2124339805030 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 95168.6 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1437552
telemt_connections_bad_total 35468
telemt_connections_current 685
telemt_connections_me_current 685
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27916
telemt_upstream_connect_attempt_total 44538
telemt_upstream_connect_success_total 44399
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 44510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 759
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2058
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 825
telemt_me_idle_close_by_peer_total 825
telemt_me_route_drop_no_conn_total 498235
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1275713
telemt_me_endpoint_quarantine_total 765
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 783
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
telemt_desync_total 7971
telemt_desync_full_logged_total 2423
telemt_desync_suppressed_total 5548
telemt_desync_frames_bucket_total{bucket="1_2"} 1940
telemt_desync_frames_bucket_total{bucket="3_10"} 3079
telemt_desync_frames_bucket_total{bucket="gt_10"} 2952
telemt_pool_swap_total 102
telemt_pool_force_close_total 2658
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 37250
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35140
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34592
telemt_me_writer_teardown_success_total{mode="normal"} 38078
telemt_me_writer_teardown_noop_total 37254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75332
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.897556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75332
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1271656
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 25054328965 (23.33 GB)
telemt_user_octets_to_client{user="hello"} 539236336275 (502.20 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 177366.3 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13183122
telemt_connections_bad_total 1563007
telemt_connections_current 1085
telemt_connections_me_current 1085
telemt_handshake_timeouts_total 379027
telemt_upstream_connect_attempt_total 67661
telemt_upstream_connect_success_total 67324
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2639
telemt_me_reconnect_success_total 1379
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1347
telemt_me_route_drop_no_conn_total 4465075
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9963287
telemt_me_endpoint_quarantine_total 1210
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_warm_current 23
telemt_desync_total 41604
telemt_desync_full_logged_total 13567
telemt_desync_suppressed_total 28037
telemt_desync_frames_bucket_total{bucket="1_2"} 10003
telemt_desync_frames_bucket_total{bucket="3_10"} 15308
telemt_desync_frames_bucket_total{bucket="gt_10"} 16293
telemt_pool_swap_total 196
telemt_pool_force_close_total 5357
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 61012
telemt_me_writer_removed_unexpected_total 1296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4934
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55655
telemt_me_writer_teardown_success_total{mode="normal"} 62349
telemt_me_writer_teardown_noop_total 61014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123363
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.570473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123363
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1206
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9930129
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 193887626916 (180.57 GB)
telemt_user_octets_to_client{user="hello"} 4396018731772 (4.00 TB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 177362.9 (49h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11469591
telemt_connections_bad_total 1305952
telemt_connections_current 837
telemt_connections_me_current 837
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 302551
telemt_upstream_connect_attempt_total 94166
telemt_upstream_connect_success_total 93321
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 93959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10057
telemt_me_reconnect_success_total 2430
telemt_me_reader_eof_total 2270
telemt_me_idle_close_by_peer_total 2269
telemt_me_seq_mismatch_total 84
telemt_me_route_drop_no_conn_total 5624863
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8863436
telemt_me_endpoint_quarantine_total 1360
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1329
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 16
telemt_desync_total 41177
telemt_desync_full_logged_total 13206
telemt_desync_suppressed_total 27971
telemt_desync_frames_bucket_total{bucket="1_2"} 10564
telemt_desync_frames_bucket_total{bucket="3_10"} 15159
telemt_desync_frames_bucket_total{bucket="gt_10"} 15454
telemt_pool_swap_total 186
telemt_pool_force_close_total 5152
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 60795
telemt_me_writer_removed_unexpected_total 2304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55643
telemt_me_writer_teardown_success_total{mode="normal"} 63178
telemt_me_writer_teardown_noop_total 60800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.295601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 1973
telemt_me_writer_restored_fallback_total 116
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 8868888
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 156606258941 (145.85 GB)
telemt_user_octets_to_client{user="hello"} 3451732844375 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 92
```