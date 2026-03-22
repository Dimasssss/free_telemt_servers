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

# Server Metrics 2026-03-22 15:08:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64897.0 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2235926
telemt_connections_bad_total 116390
telemt_connections_current 2175
telemt_connections_me_current 2175
telemt_handshake_timeouts_total 84948
telemt_upstream_connect_attempt_total 24092
telemt_upstream_connect_success_total 24091
telemt_upstream_connect_attempts_per_request{bucket="1"} 24091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 979
telemt_me_reconnect_success_total 403
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 1784184
telemt_me_route_drop_channel_closed_total 732
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1899490
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_warm_current 37
telemt_desync_total 9459
telemt_desync_full_logged_total 2927
telemt_desync_suppressed_total 6532
telemt_desync_frames_bucket_total{bucket="1_2"} 2593
telemt_desync_frames_bucket_total{bucket="3_10"} 3552
telemt_desync_frames_bucket_total{bucket="gt_10"} 3314
telemt_pool_swap_total 71
telemt_pool_force_close_total 2167
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 21961
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20596
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19794
telemt_me_writer_teardown_success_total{mode="normal"} 22174
telemt_me_writer_teardown_noop_total 21965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 189.529033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1896376
telemt_user_connections_current{user="hello"} 2175
telemt_user_octets_from_client{user="hello"} 28861490260 (26.88 GB)
telemt_user_octets_to_client{user="hello"} 514248686796 (478.93 GB)
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 78263.3 (21h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3494905
telemt_connections_bad_total 313909
telemt_connections_current 1914
telemt_connections_me_current 1914
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 82200
telemt_upstream_connect_attempt_total 49677
telemt_upstream_connect_success_total 49077
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 49606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5641
telemt_me_reconnect_success_total 1947
telemt_me_reader_eof_total 1872
telemt_me_idle_close_by_peer_total 1872
telemt_me_route_drop_no_conn_total 3500960
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2773725
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 605
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 87
telemt_desync_total 10678
telemt_desync_full_logged_total 5916
telemt_desync_suppressed_total 4762
telemt_desync_frames_bucket_total{bucket="1_2"} 2513
telemt_desync_frames_bucket_total{bucket="3_10"} 4210
telemt_desync_frames_bucket_total{bucket="gt_10"} 3955
telemt_pool_swap_total 74
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 30986
telemt_me_writer_removed_unexpected_total 1829
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29224
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28812
telemt_me_writer_teardown_success_total{mode="normal"} 32817
telemt_me_writer_teardown_noop_total 30986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63803
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.537307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63803
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1658
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 2785138
telemt_user_connections_current{user="hello"} 1914
telemt_user_octets_from_client{user="hello"} 33808717863 (31.49 GB)
telemt_user_octets_to_client{user="hello"} 601447213262 (560.14 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 153123.4 (42h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15062288
telemt_connections_bad_total 1370553
telemt_connections_current 3618
telemt_connections_me_current 3618
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 365766
telemt_upstream_connect_attempt_total 69624
telemt_upstream_connect_success_total 69529
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1658
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2557
telemt_me_reconnect_success_total 1324
telemt_me_reader_eof_total 1263
telemt_me_idle_close_by_peer_total 1262
telemt_me_route_drop_no_conn_total 13718259
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12062392
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1137
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 48526
telemt_desync_full_logged_total 15258
telemt_desync_suppressed_total 33268
telemt_desync_frames_bucket_total{bucket="1_2"} 10934
telemt_desync_frames_bucket_total{bucket="3_10"} 18992
telemt_desync_frames_bucket_total{bucket="gt_10"} 18600
telemt_pool_swap_total 165
telemt_pool_force_close_total 5601
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 916
telemt_me_draining_writers_reap_progress_total 50353
telemt_me_writer_removed_unexpected_total 1218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46490
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5145
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44752
telemt_me_writer_teardown_success_total{mode="normal"} 50876
telemt_me_writer_teardown_noop_total 50403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101279
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 288.868973
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101279
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 916
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1137
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 12063925
telemt_user_connections_current{user="hello"} 3618
telemt_user_octets_from_client{user="hello"} 168595920893 (157.02 GB)
telemt_user_octets_to_client{user="hello"} 3089356594811 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1574
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 153124.7 (42h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10863878
telemt_connections_bad_total 1046406
telemt_connections_current 2195
telemt_connections_me_current 2195
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 321257
telemt_upstream_connect_attempt_total 81838
telemt_upstream_connect_success_total 80688
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3851
telemt_me_reconnect_success_total 1546
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1421
telemt_me_route_drop_no_conn_total 4312561
telemt_me_route_drop_channel_closed_total 476
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8109966
telemt_me_endpoint_quarantine_total 962
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1159
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
telemt_me_writers_active_current 41
telemt_desync_total 36004
telemt_desync_full_logged_total 12094
telemt_desync_suppressed_total 23910
telemt_desync_frames_bucket_total{bucket="1_2"} 8845
telemt_desync_frames_bucket_total{bucket="3_10"} 13856
telemt_desync_frames_bucket_total{bucket="gt_10"} 13303
telemt_pool_swap_total 163
telemt_pool_force_close_total 5045
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 48700
telemt_me_writer_removed_unexpected_total 1453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45534
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43655
telemt_me_writer_teardown_success_total{mode="normal"} 50010
telemt_me_writer_teardown_noop_total 48716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.735590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8048889
telemt_user_connections_current{user="hello"} 2195
telemt_user_octets_from_client{user="hello"} 202363652233 (188.47 GB)
telemt_user_octets_to_client{user="hello"} 3626459376190 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 656
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 153096.0 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10305882
telemt_connections_bad_total 881220
telemt_connections_current 3030
telemt_connections_me_current 3030
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 328828
telemt_upstream_connect_attempt_total 67062
telemt_upstream_connect_success_total 66138
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4545
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 5085984
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7780936
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1120
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 27
telemt_desync_total 35647
telemt_desync_full_logged_total 11812
telemt_desync_suppressed_total 23835
telemt_desync_frames_bucket_total{bucket="1_2"} 9031
telemt_desync_frames_bucket_total{bucket="3_10"} 13625
telemt_desync_frames_bucket_total{bucket="gt_10"} 12991
telemt_pool_swap_total 159
telemt_pool_force_close_total 4990
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 49143
telemt_me_writer_removed_unexpected_total 1747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45881
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 533
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44153
telemt_me_writer_teardown_success_total{mode="normal"} 50799
telemt_me_writer_teardown_noop_total 49214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100013
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3168.609733
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100013
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1607
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7774231
telemt_user_connections_current{user="hello"} 3030
telemt_user_octets_from_client{user="hello"} 179894336961 (167.54 GB)
telemt_user_octets_to_client{user="hello"} 3226952626713 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1314
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 23368.6 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9864910
telemt_connections_bad_total 605873
telemt_connections_current 4951
telemt_connections_me_current 4951
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 159303
telemt_upstream_connect_attempt_total 29740
telemt_upstream_connect_success_total 28266
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 29300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4767
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 5529
telemt_me_reconnect_success_total 606
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 24648343
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8230531
telemt_me_endpoint_quarantine_total 143
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 176
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
telemt_desync_total 12432
telemt_desync_full_logged_total 3180
telemt_desync_suppressed_total 9252
telemt_desync_frames_bucket_total{bucket="1_2"} 2156
telemt_desync_frames_bucket_total{bucket="3_10"} 5070
telemt_desync_frames_bucket_total{bucket="gt_10"} 5206
telemt_pool_swap_total 21
telemt_pool_force_close_total 888
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 6152
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 268
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5264
telemt_me_writer_teardown_success_total{mode="normal"} 6633
telemt_me_writer_teardown_noop_total 6157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12790
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.930508
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12790
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 8245031
telemt_user_connections_current{user="hello"} 4951
telemt_user_octets_from_client{user="hello"} 48895242395 (45.54 GB)
telemt_user_octets_to_client{user="hello"} 239443060380 (223.00 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 1994
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 153095.5 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10039955
telemt_connections_bad_total 834441
telemt_connections_current 2518
telemt_connections_me_current 2518
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 220188
telemt_upstream_connect_attempt_total 91569
telemt_upstream_connect_success_total 90631
telemt_upstream_connect_fail_total 807
telemt_upstream_connect_attempts_per_request{bucket="1"} 91438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 807
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71536
telemt_me_reconnect_success_total 2513
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2224
telemt_me_route_drop_no_conn_total 5009002
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7929134
telemt_me_endpoint_quarantine_total 1025
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1138
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 17
telemt_desync_total 40914
telemt_desync_full_logged_total 14010
telemt_desync_suppressed_total 26904
telemt_desync_frames_bucket_total{bucket="1_2"} 8307
telemt_desync_frames_bucket_total{bucket="3_10"} 15876
telemt_desync_frames_bucket_total{bucket="gt_10"} 16731
telemt_pool_swap_total 156
telemt_pool_force_close_total 4652
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 51934
telemt_me_writer_removed_unexpected_total 2270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48695
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47282
telemt_me_writer_teardown_success_total{mode="normal"} 54222
telemt_me_writer_teardown_noop_total 51935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.168080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7929473
telemt_user_connections_current{user="hello"} 2518
telemt_user_octets_from_client{user="hello"} 180350161875 (167.96 GB)
telemt_user_octets_to_client{user="hello"} 2979139813733 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 709
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 89931.8 (24h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10397167
telemt_connections_bad_total 379932
telemt_connections_current 3777
telemt_connections_me_current 3777
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4388732
telemt_upstream_connect_attempt_total 43581
telemt_upstream_connect_success_total 43264
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 43572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_reconnect_attempts_total 47962
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1141
telemt_me_route_drop_no_conn_total 3867246
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4988061
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 27224
telemt_desync_full_logged_total 9178
telemt_desync_suppressed_total 18046
telemt_desync_frames_bucket_total{bucket="1_2"} 5504
telemt_desync_frames_bucket_total{bucket="3_10"} 10763
telemt_desync_frames_bucket_total{bucket="gt_10"} 10957
telemt_pool_swap_total 94
telemt_pool_force_close_total 2923
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 303
telemt_me_draining_writers_reap_progress_total 30796
telemt_me_writer_removed_unexpected_total 1206
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27873
telemt_me_writer_teardown_success_total{mode="normal"} 32031
telemt_me_writer_teardown_noop_total 30803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.549693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 303
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4981910
telemt_user_connections_current{user="hello"} 3777
telemt_user_octets_from_client{user="hello"} 107491726000 (100.11 GB)
telemt_user_octets_to_client{user="hello"} 1870391794738 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70902.1 (19h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899617
telemt_connections_bad_total 11791
telemt_connections_current 1210
telemt_connections_me_current 1210
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17940
telemt_upstream_connect_attempt_total 35304
telemt_upstream_connect_success_total 35216
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 35288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1591
telemt_me_reconnect_success_total 674
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 307954
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799195
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 590
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4441
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 3092
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1756
telemt_desync_frames_bucket_total{bucket="gt_10"} 1639
telemt_pool_swap_total 75
telemt_pool_force_close_total 1881
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 29119
telemt_me_writer_removed_unexpected_total 628
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27535
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27238
telemt_me_writer_teardown_success_total{mode="normal"} 29770
telemt_me_writer_teardown_noop_total 29121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.332591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 800297
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 14820773717 (13.80 GB)
telemt_user_octets_to_client{user="hello"} 369183118859 (343.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 153100.5 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12328841
telemt_connections_bad_total 1436261
telemt_connections_current 4709
telemt_connections_me_current 4709
telemt_handshake_timeouts_total 336969
telemt_upstream_connect_attempt_total 57274
telemt_upstream_connect_success_total 57048
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 57224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 2233
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1157
telemt_me_idle_close_by_peer_total 1157
telemt_me_route_drop_no_conn_total 4117675
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9309514
telemt_me_endpoint_quarantine_total 1036
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1141
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 39
telemt_desync_total 38186
telemt_desync_full_logged_total 12473
telemt_desync_suppressed_total 25713
telemt_desync_frames_bucket_total{bucket="1_2"} 9097
telemt_desync_frames_bucket_total{bucket="3_10"} 14154
telemt_desync_frames_bucket_total{bucket="gt_10"} 14935
telemt_pool_swap_total 169
telemt_pool_force_close_total 4678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 51549
telemt_me_writer_removed_unexpected_total 1112
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46871
telemt_me_writer_teardown_success_total{mode="normal"} 52692
telemt_me_writer_teardown_noop_total 51551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.573369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 1047
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 9279056
telemt_user_connections_current{user="hello"} 4709
telemt_user_octets_from_client{user="hello"} 178916689384 (166.63 GB)
telemt_user_octets_to_client{user="hello"} 4097653295248 (3.73 TB)
telemt_user_unique_ips_current{user="hello"} 1860
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 153097.3 (42h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10675130
telemt_connections_bad_total 1191118
telemt_connections_current 3925
telemt_connections_me_current 3925
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 274998
telemt_upstream_connect_attempt_total 83071
telemt_upstream_connect_success_total 82451
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 82987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2023
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_reconnect_attempts_total 8802
telemt_me_reconnect_success_total 2021
telemt_me_reader_eof_total 1887
telemt_me_idle_close_by_peer_total 1887
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5366674
telemt_me_route_drop_channel_closed_total 340
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8248569
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1146
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 88
telemt_me_writers_warm_current 38
telemt_desync_total 37748
telemt_desync_full_logged_total 12186
telemt_desync_suppressed_total 25562
telemt_desync_frames_bucket_total{bucket="1_2"} 9402
telemt_desync_frames_bucket_total{bucket="3_10"} 14083
telemt_desync_frames_bucket_total{bucket="gt_10"} 14263
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 590
telemt_me_draining_writers_reap_progress_total 50979
telemt_me_writer_removed_unexpected_total 1912
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47644
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46475
telemt_me_writer_teardown_success_total{mode="normal"} 52958
telemt_me_writer_teardown_noop_total 50984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103942
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.853743
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103942
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 590
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8254815
telemt_user_connections_current{user="hello"} 3925
telemt_user_octets_from_client{user="hello"} 144989693601 (135.03 GB)
telemt_user_octets_to_client{user="hello"} 3145120710027 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1760
telemt_user_unique_ips_recent_window{user="hello"} 321
```